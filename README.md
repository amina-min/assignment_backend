# assignment_backend
curl --location --request POST 'http://localhost:9005/api/ex/user/user_login' \
--header 'Content-Type: application/json' \
--data-raw '{
    
    "userId" : 5111,
    "password" : "amina123"
   
}'



curl --location --request POST 'http://localhost:9005/api/ex/user/user_add' \
--header 'Content-Type: application/json' \
--data-raw '{
    
    "userId" : 5113,
    "mobile":"0172787000",
    "password" : "amina123"
   
}'


curl --location --request POST 'http://localhost:9005/api/ex/user/reset_password' \
--header 'Content-Type: application/json' \
--data-raw '{
    
    "userId" : 5113,
    "mobile":"0172787000",
    "password" : "abc123"
   
}'


curl --location --request PUT 'http://localhost:9005/api/ex/user/update_password' \
--header 'Content-Type: application/json' \
--data-raw '{
    
    "userId" : 5113,
    "mobile":"0172787000",
    "password" : "abc12"
   
}'
