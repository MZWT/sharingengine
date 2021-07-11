# Sharingengine

1.Cloning project to PC

`=> https://github.com/MZWT/sharingengine.git`

2.Pull source from develop

`=> cd sharingengine`

`=> git checkout develop`

`=> git pull origin develop`
 
3.Create/start container in docker

`=> docker-compose up -d`

5.Enter to PHP container & Laravel App and run migrate command

`=> docker-compose exec app bash`

`=> cd laravel-app`

`=> composer install`

`=> php artisan migrate`

6.Run laravel app on browser

`http://localhost:8000/`

7.Running React App 

`=> cd ..(repeatly run(4 times))`

`=> exit`

`=> cd react-app`

`=> npm install`

`=> npm start`

8.Run React app on browser

`http://localhost:3000/`
