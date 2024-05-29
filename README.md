curl --location --request GET 'localhost:8080/oauth/token' \
--header 'Content-Type: application/x-www-form-urlencoded' \
--header 'Authorization: ••••••' \
--data-urlencode 'grant_type=password' \
--data-urlencode 'username=user' \
--data-urlencode 'password=password'
