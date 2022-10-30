# user_cart_microservice_esa

* Clone the repo
* Run pip install -r requirements.txt
* Start the service by running python app.py, it should start the server on port 5555
* Once the server is running, go to user_cart microservice and follow the instructions over there
* Note: product_service server has tro be up and running for user_cart service to work

Once both are up and running we can make requests to http://localhost:5555/rest/v1/users/uuid/cart PUT to add a product or GET to get products

* Note: use 1 or 2 or 3 as uuid in requests and test it
