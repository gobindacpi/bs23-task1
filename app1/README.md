
#Create Laravel project for app1
```
composer create-project laravel/laravel app1
```
To change "hellow I am App1", go to "vi /app1/public/index.php", type below and save&exit.

```
<?php
echo "Hello I am App1 \n";
?>
```

#Now build the docker image
```
docker build -t app1 .
```
#Then rename name the Docker image 
```
docker tag app1 gobindacpi/bs23-app1:01
```
#finally push to docker hub
'''
docker push gobindacpi/bs23-app1:01
```
