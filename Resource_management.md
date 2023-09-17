# Resource management:
## Resource:
- Objects used to manage services in azure.
- Represent service life cycle.
- Saved as JSON (JavaScript Object Notation) defination.

### Basic json format:

<img width="354" alt="image" src="https://github.com/pilipi-puu-puu/Microsoft_Azure/assets/87390353/d25c2d18-fa05-4912-bb24-e4122c61d50f">

---

## Resource group:
- Grouping of resources.
- Holds logically related resources.

- Organized by:
  - Departments
  - Type
  - Life cycle (app, environment)
  - Billing, location or combination of those.
<img width="333" alt="image" src="https://github.com/pilipi-puu-puu/Microsoft_Azure/assets/87390353/a4315d4a-d708-4584-b79e-64264562efe5">

- Creating a resource in Azure CLI:
  - Go to the console.
  - az login
  - `az group create --name az-900-2 --location "north europe"`
  - Adding the resource(az-900-2) into a resource group(anushka14123dh)
  - `az storage account create --name anushka14123dh --resource-group az-900-2 --location "north europe"`

## summary:

<img width="520" alt="image" src="https://github.com/pilipi-puu-puu/Microsoft_Azure/assets/87390353/05b4210e-bcc3-4f4e-88fb-091edee99dfd">

---

## Resource manager:

<img width="677" alt="image" src="https://github.com/pilipi-puu-puu/Microsoft_Azure/assets/87390353/32314d97-4bce-4a63-8f31-b44639e05d97">


     
