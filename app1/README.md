
Create Laravel project for app1
```
composer create-project laravel/laravel app1
```
Now build the docker image
```
docker build -t app1 .
```
Then rename name the Docker image 
```
docker tag app1 munnaeeebd/bs23:app1
```
finally push to docker hub
''''
docker push gobindacpi/bs23-app1:01
```
