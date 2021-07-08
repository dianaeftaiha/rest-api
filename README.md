Based on  Build a Simple REST API in PHP, by Krasimir Hristozov 

For tutorial, visit https://developer.okta.com/blog/2019/03/08/simple-rest-api-php


You can test the API with a tool like Postman. First, go to the project directory and start the PHP server:


php -S 127.0.0.1:8000 -t public


Then connect to 127.0.0.1:8000 with Postman and send http requests. 


Note: when making PUT and POST requests, make sure to set the Body type to raw, then paste the payload in JSON format and set the content type to JSON (application/json).


Endpoints 

// return all records

GET /person

// return a specific record

GET /person/{id}

// create a new record

POST /person

// update an existing record

PUT /person/{id}

// delete an existing record

DELETE /person/{id}