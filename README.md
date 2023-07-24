# Passportwithmedia
This example for laravel passport with medialibrary
  
# Installation
camposer update or composer install

# Auth Api
http://127.0.0.1:8000/api/register

curl --location --request POST 'http://127.0.0.1:8000/api/register' \
--header 'Accept: application/json' \
--form 'name="sarim ali"' \
--form 'email="sarim2@gmail.com"' \
--form 'password="123456"'

http://127.0.0.1:8000/api/login

curl --location --request POST 'http://127.0.0.1:8000/api/login' \
--header 'Accept: application/json' \
--form 'email="sarim2@gmail.com"' \
--form 'password="123456"'
