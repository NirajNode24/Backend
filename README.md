Download and extract the peoject 

run npm i to install the the dependies 

in you local db or cloud of mysql instance

run this codes 

CREATE
DATABASE IF
NOT
EXISTS
customer_service; USE customer_service;
CREATE
TABLE
IF
NOT
EXISTS
customer_requests (     id
INT
AUTO_INCREMENT
PRIMARY
KEY,     user_id
VARCHAR
(255)
NOT
NULL
,     category
VARCHAR
(255)
NOT
NULL
,     comments TEXT
NOT
NULL
, created_at
TIMESTAMP
DEFAULT
CURRENT_TIMESTAMP
);

it having three end points 

http://localhost:3000/auth/google to initiate Google OAuth login.
http://localhost:3000/customer-service/submit to submit a customer service request (POST request with body: { userId, category, comments }).
http://localhost:3000/customer-service/requests/:category to retrieve customer

i implemented in frontend App

thank you for the opportunity

Niraj kumar

