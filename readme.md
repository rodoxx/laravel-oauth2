## Laravel PHP Framework with oAuth2.0 server 

1. clone this project 
 ``` git clone https://github.com/rodoxx/laravel-oauth2.git foldername ```

2. tell composer to download the required libraries 
```composer update ```
3. configure database setting in ".env" file 
4. then run  " ``` php artisan migrate ``` " , if "Nothing to migrate." message apeared , run " ``` php artisan migrate:reset ``` "
5. run " ```php artisan db:seed ``` " to add test client and user
6. to test the server run   ``` php artisan serve ```  , then in REST Client ( eg. postman ) , make a POST request  to ( http://localhost:8000/oauth/access_token )

###test user:  
username=test@test.com   
password = password   

client App :   
grant_type=password   
client_id = GXvOWazQ3lA6YSaFji   
client_secret =GXvOWazQ3lA.6/YSaFji   
 
