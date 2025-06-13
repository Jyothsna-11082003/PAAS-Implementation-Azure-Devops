# Cleanup with Terraform Destroy

To destroy all provisioned resources:

### Steps:
- Enable the `Terraform Destroy` task
- Add `--auto-approve` in additional arguments
- Run pipeline to remove infra

> Confirm if storage account is excluded (to retain state if needed)

