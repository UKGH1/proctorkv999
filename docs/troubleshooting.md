# Troubleshooting

## Common Issues and Resolutions

### 1. Deployment Errors
**Issue:** Insufficient permissions error during deployment.
**Resolution:** Verify that your Azure account has Contributor or Owner access on the subscription.

### 2. Access Denied
**Issue:** Applications cannot access secrets or keys.
**Resolution:**
- Verify access policies in the Key Vault.
- Ensure the application identity (managed identity or service principal) is added with appropriate permissions.

### 3. Key Vault Not Found
**Issue:** Terraform script fails to locate the Key Vault.
**Resolution:** Double-check the resource group and Key Vault name provided in the configuration files.

## Debugging Tips
- Use the Backstage logs to trace issues.
- Enable diagnostic logs for the storage account in Azure for detailed error information.

## Contact Support
For further assistance, contact your Azure administrator or refer to [Azure Documentation](https://learn.microsoft.com/azure/key-vault).
