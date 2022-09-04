#Create Laravel project for app2
```
composer create-project laravel/laravel app2
```
#To change "hellow I am App2", go to "vi /app2/public/index.php", type below and save&exit.
```
<?php
echo "Hello I am App2 \n";
?>
```
#Now build the docker image
```
docker build -t app2 .
```
#Then rename name the Docker image
```
docker tag app2 gobindacpi/bs23-app2:01
```
#finally push to docker hub 
''' 
docker push gobindacpi/bs23-app2:01
```

