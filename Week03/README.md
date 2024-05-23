## Crearte a Virtual Machine on Azure using ARM Template
az group create --name RS --location eastus
az deployment group create --resource-group RS --template-file ./lab1.json
