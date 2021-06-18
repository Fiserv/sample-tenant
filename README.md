README.md file
# Fiserv Developing Studio Sample Repo

    Sample tenants code for Fiserv Dev Portal

## Run Tenant Application
- To Start tenant:
```Shell
    ./start.sh
```
- Run unittest
```Shell
    ./unittest.sh
```
## Directory structure
/docs - all markdown files are to be placed in this directory
/assets - upload your static assets like image etc here
tenant_api.json: Tenant Provider API
product_layout.yaml: Yaml spec for product layout page
api_swagger.yaml: Tenant APIs in OpenAPI 3.0 Spec

## Configurations
- /resources/config.yml : Update below configuration to point to tenant content github repo
```Shell 

contentpath:
  tenantProviderApiFile:     "tenant_api.json"
  apiSpecYamlFile:            "api_swagger.yaml"
  productLayoutFile:          "product_layout.yaml"


github:
  gitHubRawContentHost:       "https://raw.githubusercontent.com"
  gitHubSourceOwner:          "Fiserv"
  gitHubSourceRepo:           "<tenant_repo>"
  gitHubContentBranch:        "main" 
  gitHubAuthToken:            "<auth_token>"
  gitHubUser:                 "<username>"

    ```
## Code
- routers.go: Contains the routes that tenants need to implement.
