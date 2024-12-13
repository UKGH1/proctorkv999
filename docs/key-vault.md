# Azure Resource Configuration: Key Vault

## Setting up Key Vault
Follow these steps to configure Azure Key Vault as per the template:

1. **Create the Key Vault**:
    - Navigate to the Azure Portal.
    - Select **Create a resource** > **Key Vault**.
    - Specify the name, region, and pricing tier.
2. **Assign Access Policies**:
    - Define policies to manage access to the secrets, keys, and certificates.
    - Use Azure RBAC for granular control.
3. **Enable Integration**:
    - Connect the Key Vault to Azure services such as App Service or Azure Functions for secure key management.

### Key Considerations:
- Enable **Soft Delete** and **Purge Protection**.
- Limit access to trusted networks only.
