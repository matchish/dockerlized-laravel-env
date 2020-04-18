## dockered laravel environment for developers
Build Laravel's development environment using docker.
PHP7.4/MySQL8.0/nginx/redis/node

## install docker for your OS

- [Build for Mac](https://github.com/ucan-lab/docker-laravel/wiki/Build-for-Mac)
- [Build for Windows](https://github.com/ucan-lab/docker-laravel/wiki/Build-for-Windows)

## Build & Run
1. clone this repository on your working directory
3. make directory called dist and create laravel project with this command 
`$ mkdir dist`
`$ cd dist && composer create-project --prefer-dist laravel/laravel .`
2. run this command `$ docker-compose build && docker-compsoe up -d`
3. you can check if the container is runngin by `$ docker ps`