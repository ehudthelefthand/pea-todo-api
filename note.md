REST API - Represent State Transfer 
eCommerce
Resource: 
- Product
- User
- Shop
- Category
- Price
- Promotion Banner
- Payment method
- Stock
- Order
- Reward
- Delivery
- Cart

Product
   -  /products
HTTP
- HTTP Method
- GET, POST, PUT, PATCH, DELETE, (OPTIONS)

Create Product
- POST /products
Lookup Product
- GET /products
Lookup A Product by ID
- GET /products/:id
Update Product by ID
- PUT /products/:id  <--- Replace Product
- PATCH /products/:id <--- Update Product Partially
Delete Product by ID
- DELETE /products/:id
Search Product
- GET /products?key=some-keyword

Status Code
- Success: 200
    - Created : 201
    - No Content: 204
- Not Found: 404
- Bad Request: 400
- Unprocess Entity: 422
- Internal Server Error: 500
- Unauthorized: 401
- Forbidden: 403
- Redirect: 301, 302


Todo
- ID: UUID
- Name: String
- Completed: Boolean


Validation
- Validation + ORM
- Validation + API