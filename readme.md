## Shopmart RESTful API 

A simple RESTful API that allows an administrator  to create, read, edit and delete products

## Shopmart End Points

### GET /products

The above end point returns all products

### GET /products/id

The above end point returns a product based on the id provided

### GET /customers

The above end point returns cutomers 

### POST /products

The above end point creates a product. You are required to submit the product data in the body of the request (as JSON) : 
The data includes :

- productName (required)
- description (required)
- price (required)
- photURL,
- bestSeller (required)
- productCategory (required)


### POST /customers

The above end point creates a customer. You are required to submit the customer data in the body of the request (as JSON) : 
The data includes :
- firstName (required)
- lastName (required)
- email (required)
- phoneNumbers,
- password (required)


### PUT /products/id

The above end point updates a resort based on the id provided. You are required to submit the  resort destination data, that is require to be updated,in the body of the request (as JSON) : The data could include ANY of the following :

- title (required)
- description (required)
- price (required)
- imagePath (required),
- featured (required)

### DELETE /Product/id

The above end point deletes a product based on the id provided

## Rules to Set up application

1. Clone source code by running: **git clone GITHUP_PROJECT_URL . **
2. After Cloning, re-install ALL 3rd party dependencies by running **npm install**
3. Create a folder within the project called **config**
4. Within the **config** folder, create a file called **keys.env**
5. Within the **keys.env** file, create the below environment variables :
   - **MONGODB_QUERY_STRING** - Assign your Database Connection String to the variable
   - **PORT** - Assign 5000
6. Run application by running : **npm run dev**# shopmart-back-end

