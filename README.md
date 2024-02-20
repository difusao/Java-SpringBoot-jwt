# Java-SpringBoot-jwt
spring-jwt

#cURL
Login:
```
curl --location 'http://localhost:8080/rest/auth/login' \
--header 'Content-Type: application/json' \
--data-raw '{
    "email": "ex@example.com",
    "password": "123456"
}'
```
Home:
```
curl --location 'http://localhost:8080/rest/home' \
--header 'Authorization: Bearer eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJleEBleGFtcGxlLmNvbSIsImV4cCI6MTkyNDQ2NDQ1MX0.sS-sFTsfuMvKOIMQvRQMn2LZ3YWmicQgQbB2tKC5TWc' \
--data ''
```