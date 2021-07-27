# (NOT WORKING YET, BECAUSE IT IS REQUIRED TO ASSIGN AAD ROLE TO THE SERVICE PRINCIPAL AND THIS IS NOT SUPPORTED BY ARM TEMPLATES )
- In this deployment, first a user assigned managed identity is created
- Then role is assigned to this identity in SUBSCRIPTION LEVEL TEMPLATE (to assign role at subscription scope)
- Then a deployment script to create the ad app and service principal
- The main template is also SUBSCRIPTION LEVEL TEMPLATE because of one of the nested template is SUBSCRIPTION LEVEL TEMPLATE.

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fosamaemumba%2Faad_app_and_service_principal_ARM_deployment%2Fmain%2Fazuredeploy.json)
