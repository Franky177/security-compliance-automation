# security-compliance-automation
Automation project for cloud security and compliance using Terraform. Integrates security scans, vulnerability assessments, and compliance checks into a CI/CD pipeline. Includes continuous monitoring, automated reporting, and enforcement of best practices to enhance infrastructure security
## Table of Contents
- [Project Description](#project-description)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [CI/CD Pipeline](#ci/cd-pipeline)
- [Usage](#usage)
- [Security Features](#security-features)
- [Contributing](#contributing)
- [License](#license)
## Technologies Used
- **Terraform**: Infrastructure as Code (IaC) for provisioning Google Cloud resources.
- **Trivy**: Security tool for scanning vulnerabilities.
- **GitHub Actions**: CI/CD platform for automating workflows.
- **Google Cloud Platform (GCP)**: Cloud provider for hosting infrastructure.
## Setup and Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Franky177/security-compliance-automation.git
   cd security-compliance-automation
## CI/CD Pipeline
The project uses GitHub Actions to automate security scans with Trivy. The pipeline is triggered on every push or pull request to the main branch.

- **Trivy Scan:** Runs a vulnerability scan on the cloud infrastructure.
- **Results:** The results of the scan are displayed in the Actions tab of the GitHub repository.

Workflow file: `.github/workflows/ci.yml`
## Usage
- **Trigger the CI Pipeline:**
  Push changes to the repository or create a pull request to trigger the CI pipeline.
- **View Results:**
  Go to the Actions tab in GitHub to view the results of the Trivy security scan.
## Security Features
- **Automated Vulnerability Scanning:** Uses Trivy to detect vulnerabilities in the infrastructure.
- **Continuous Monitoring:** The CI pipeline ensures ongoing security by scanning on every code change.
