# Terraform Build Pipeline in Azure DevOps

### Tasks
1. **NuGet Tool Installer**
2. **NuGet Restore**
3. **Build .NET App**
4. **Copy Files**
   - Contents: `**/*.tf`
5. **Publish Artifacts**

> This prepares `.tf` files for Release pipeline.

### State File Handling
- Create a Storage Account in Azure
- Create a Container (e.g., `tfstate`)
- Add backend.tf in Terraform folder to store state file remotely

### Storage Account
- Used to store statefile(metadata).It can be stored if that terraform files deleted. 
