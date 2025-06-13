# Creating a Service Connection in Azure DevOps

### 1. Register an App in Azure:
- Go to **Azure Portal > Azure Active Directory > App Registrations > New registration**
- Name: `my-devops-app`
- Redirect URI: Leave default

### 2. Assign Role:
- Go to **Subscriptions > Access Control (IAM) > Add Role Assignment**
- Role: **Contributor**
- Assign access to: **User, group, or service principal**
- Select your app registration name

### 3. Create Service Connection in Azure DevOps:
- Go to **Azure DevOps > Project Settings > Service Connections > Azure Resource Manager > Service Principal (Manual)**
- Fill in:
  - Subscription ID
  - Subscription Name
  - Tenant ID
  - Service Principal ID (App ID)
  - Service Principal Key (Secret)
- Verify and Save

