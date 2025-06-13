# Release Pipeline – Deploy App Using Terraform

### Artifacts
- Link the artifact from Build pipeline

### Stage 1: Terraform Infra Provision
- Tasks:
  - Install Terraform Tool
  - Terraform Init
  - Terraform Validate
  - Terraform Plan
  - Terraform Apply (`--auto-approve`)
- Inputs:
  - Storage account name
  - Resource group
  - Service connection

### Stage 2: Deploy to App Service
- Tasks:
  - Azure App Service Deploy
  - Set `.dll` path
  - Provide app service name, subscription

