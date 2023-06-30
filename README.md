Step 0:
        - Start the node server
        <br>
Step 1: 
By Using POSTMAN API we can hit all the route endpoints.

- PUT request on POSTMAN API to update an existing product by ID:
  --"http://localhost:3000/product/<id>"
  <id> must be an integer
- GET request on POSTMAN API to get a specific product by ID:
  --"http://localhost:3000/product/<id>
  <id> must be an integer
- POST request on POSTMAN API to insert new order:
  --"http://localhost:3000/order"
- GET request on POSTMAN API to get specific order by ID:
  --"http://localhost:3000/order/<id>"
  <id> must be an integer

  <br>
  <h4>Authentication</h4>
  <br>
  <p>I have saved the initial jsonwebtoken on a seperate file named as "accesstoken.js". The reason for it is that due to eid holidays, I wasn't able to give time on the task yesterday and had to implement the entire task within 16 hours.</p>
  <br>
  <p>Then in each controller before exeuting a route specific function, the "authenticate token" is executed to verify the jsonwebtoken.</p>
