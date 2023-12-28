# Terraform Resume Site

## Overview

The Terraform Resume Site is a project hosting a personal resume website, ready for deployment to an AWS S3 bucket using Terraform. It features a structured layout with infrastructure configurations and website assets.

## Getting Started

### Prerequisites

- Terraform installed.
- AWS CLI configured with appropriate permissions.

### Project Structure

- **Infrastructure Files:** Contains Terraform files (`main.tf`, `outputs.tf`, `variables.tf`, `versions.tf`) for setting up the infrastructure.
- **Site Assets:** Houses the HTML files (`elements.html`, `generic.html`, `index.html`), CSS, JavaScript, and Sass files for the website's front end. It also includes license and readme texts specific to the website.

### Deployment

1. **Initialize Terraform:**
   - Navigate to the `infrastructure-files` directory.
   - Run the command:
     ```
     terraform init
     ```

2. **Apply Terraform Configuration:**
   - Execute:
     ```
     terraform apply
     ```
   - Confirm the deployment when prompted.

## Local Development

- **HTML:** Edit HTML files in the `site-assets` directory.
- **CSS and JavaScript:** Modify these in the `site-assets/assets/css` and `site-assets/assets/js` directories.
- **Sass:** Located in `site-assets/assets/sass`, with various subdirectories for organization (e.g., `base`, `components`, `layout`).

## Contributions

- Fork the repository.
- Create a new branch for your feature.
- Make changes and test locally.
- Submit a pull request with a clear description of your changes.
