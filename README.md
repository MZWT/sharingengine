# Sharingengine

### 1. Cloning project to PC

From terminal or command line, run the following command
 ```
 git clone https://github.com/MZWT/sharingengine.git
 ```

### 2. Pull source from develop
```
cd sharingengine
git checkout develop
git pull origin develop
```

### 3. Add .env file in sharingengine>laravel-app>.env
```
cp laravel-app/.env.local laravel-app/.env
```
 
### 4. Create/start container in docker
```
docker-compose up -d
```

### 5. Enter to PHP container & Laravel App and run migrate command
```
docker-compose exec app bash
cd laravel-app
composer install
php artisan migrate
```

### 6. Run laravel app on browser

http://localhost:8000/

### 7. If you do not have Node.js installed, Please download & install (if already install can skip this step.)

Can check Node install condition by running

```node -v```

[manually download link](https://nodejs.org/en/)

[reference link for installing on mac](https://qiita.com/non0311/items/664cf74d9ff4bad9cf46)


[reference link for installing on window](https://phoenixnap.com/kb/install-node-js-npm-on-windows)

### 8. Running React App
```
exit
cd react-app
npm install
npm start
```

### 9. Run React app on browser

http://localhost:3000/
