### Create laravel project with 
```
docker-compose run --rm composer create-project laravel/laravel .
```
- This is running the composer container to create the project with the laravel installer package.
- We're basically running composer in a standalone container and building it when we need to run commands and destroying it afterwards.
---
Example commands:
```
$ docker-compose run --rm composer install <vendor/package>
$ docker-compose run --rm composer dumpautoload
```