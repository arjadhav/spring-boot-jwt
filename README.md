curl --location 'localhost:8080/oauth/token' \
--header 'Content-Type: application/x-www-form-urlencoded' \
--header 'Authorization: ••••••' \
--data-urlencode 'grant_type=client_credentials'


POST /oauth/token HTTP/1.1
Host: localhost:8080
Content-Type: application/x-www-form-urlencoded
Authorization: ••••••
Content-Length: 29

grant_type=client_credentials


curl --location --request POST 'localhost:8080/oauth/token?grant_type=client_credentials' \
--header 'Authorization: Basic amF2YWludXNlLWNsaWVudDpqYXZhaW51c2Utc2VjcmV0'



