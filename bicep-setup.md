
## Install Microsoft Azure CLI 

[Installing Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows?tabs=winget)

```
winget install -e --id Microsoft.AzureCLI
```

## Install az bicep extension
```
az bicep install
```
Installing Bicep CLI v0.17.1... \
The configuration value of bicep.use_binary_from_path has been set to 'false'. \
Successfully installed Bicep CLI to "C:\Users\simon\.azure\bin\bicep.exe".

## Check az bicep extension
```
az bicep version
```
Bicep CLI version 0.17.1 (d423d61882)

## Running Az Commands
You can now run the Azure CLI with the az command from either Windows Command Prompt or PowerShell.

## An Introduction to Bicep
[What is Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview?tabs=bicep) \
[Installing Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/install) \
[Azure Module Templates](https://github.com/Azure/ResourceModules)

### Clone Azure Templates 

You want to copy the Modules from here: 
```
git clone https://github.com/Azure/ResourceModules
```


