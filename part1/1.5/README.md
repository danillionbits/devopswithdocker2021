sudo docker pull devopsdockeruh/simple-web-service:alpine

sudo docker images

REPOSITORY                          TAG       IMAGE ID       CREATED       SIZE
devopsdockeruh/simple-web-service   ubuntu    4e3362e907d5   5 weeks ago   83MB
devopsdockeruh/simple-web-service   alpine    fd312adc88e0   5 weeks ago   15.7MB

sudo docker run -d --name alpine devopsdockeruh/simple-web-service:alpine

sudo docker exec -it alpine sh

-> tail -f ./text.log

2021-04-23 07:10:55 +0000 UTC
2021-04-23 07:10:57 +0000 UTC
Secret message is: 'You can find the source code here: https://github.com/docker-hy'
2021-04-23 07:10:59 +0000 UTC
2021-04-23 07:11:01 +0000 UTC
2021-04-23 07:11:03 +0000 UTC

