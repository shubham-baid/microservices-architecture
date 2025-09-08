# Microservices Architecture Assignment

• Create a User: 

curl --location --request GET 'http://localhost:5001/users/' \
--header 'Content-Type: application/json' \
--data-raw '{
    "email": "candy@example.com",
    "name": "Candy"
}'

![Screenshot](images/create_user.png)



• Get a User: 

curl http://localhost:5001/users/3

![Screenshot](images/get_user.png)



• Create an Order: 

curl --location --request GET 'http://localhost:5002/orders' \
--header 'Content-Type: application/json' \
--data '{
    "user_id":3, 
    "product": "Tablet"
}'

![Screenshot](images/create_order.png)



• Get an Order: 

curl http://localhost:5002/orders/3

![Screenshot](images/get_order.png)

