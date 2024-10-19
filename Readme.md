# Overview 
Check subsequent Readme files for further information 
- [Infra](./infrastructure/Readme.md)
- [Backend](./backend/README.md)
- [Frontend](./frontend/README.md)

# Useful command
## Create Service principal on Azure Entra Id
```shell
az ad sp create-for-rbac --name "<your-service-principal-name>" --sdk-auth --role contributor --scopes /subscriptions/<your-subscription-id>/resourceGroups/<resource-group-name>
```
