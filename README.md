# REST  API Notes

## Designing REST APIs

### REST Methods:
- APIs expose four fundamental operations 
  - Create
  - Read
  - Update
  - Delete

APIs must also map the CRUD operations to HTTP methods

REST Method <==> CRUD Operation
    - POST <==> Create
    - GET  <==> Read
    - PUT  <==> Update
    - DELETE <==> Delete
    - OPTIONS

HTTP Options provide a way for the clients to find the operations supported by the APIs

The endpoints in a REST API follow the plural form of the resource name 

Endpoint:
/api/products
HTTP Method:
GET
Functionality:
Retrieve list of all products with details 

Endpoint:
/api/products/{id}
HTTP Method:
GET
Functionality:
Retrieve details of specific product identified by id

Endpoint:
/api/products
HTTP Method:
POST
Functionality:
Create a new product


