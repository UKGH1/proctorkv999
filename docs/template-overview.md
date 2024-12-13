# Template Overview

The **Azure Key vault Template** helps developers create a key vault in Azure using Backstage. This template supports parameterized configurations to meet diverse application needs.

## Template Structure

### 1. **Input Parameters**
The template accepts the following parameters for customization:
- `KVName`: Unique name for the key vault.
- `resourceGroupName`: Azure resource group for the key vault.
- `location`: Azure region for deployment (e.g., `eastus`).

### 2. **Resources**
The template provisions:
- Azure Key Vault

### 3. **Outputs**
After deployment, the following outputs are available:
- Key vault name

## Customization Options
Modify the `mkdocs.yaml` to add descriptions for additional resources if necessary.
