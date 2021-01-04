### To create laravel project using composer:
#### It will create laravel project inside /src directory 
- ```docker-compose run --rm composer create-project --prefer-dist laravel/laravel .``` 
#### To run application
- ```docker-compose up -d --build server```
#### To shut down application
- `docker-compose down`
#### To run artisan commands
`docker-compose run --rm artisan <command>`
#### To run npm commands
`docker-compose run --rm npm <command>`
##### App shold be running on localhost:8000