# AWS Fin Infrastructure Core

Secure and compliant foundational infrastructure for AWS Free Tier cloud architecture, managed via Terraform and automated security workflows.

## 🚀 Project Overview
This repository provisions a secure baseline VPC layout optimized for cloud applications while strictly adhering to cost and security boundaries.

## 🛡️ Security & Quality Tools
- **TFLint:** Enforces code quality, syntax rules, and catches provider misconfigurations.
- **TFSec:** Scans infrastructure code statically for security vulnerabilities (e.g., ensuring VPC flow logging standards).

## 📂 Project Structure
- `main.tf`: Core Terraform HCL resource declarations (VPC setup).
- `.github/workflows/ci.yml`: Automated GitHub Actions pipeline for continuous validation.