1) First create database eg blog

2) Update env file with database values

3) RUN composer update

4) php artisan migrate --database=system

5) php artisan key:gen

6) You should see laravel landing page.

7) RUN php artisan make:website
    Eg: Input the subdomain you have registered in nginx conf file
    
8) Visit the subdomain in browser with subdomain.domain.com/home

9) For testing if the data is coming from subdomain database, enter some value in posts table and run /posts
