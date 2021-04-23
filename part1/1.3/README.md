sudo docker run -d --name secret devopsdockeruh/simple-web-service:ubuntu
sudo docker exec -it secret bash
tail -f ./text.log


2021-04-23 06:52:43 +0000 UTC
Secret message is: 'You can find the source code here: https://github.com/docker-hy'
2021-04-23 06:52:45 +0000 UTC
2021-04-23 06:52:47 +0000 UTC
2021-04-23 06:52:49 +0000 UTC
2021-04-23 06:52:51 +0000 UTC
2021-04-23 06:52:53 +0000 UTC


Ctrl+p and Ctrl+q to read escape sequence
Ctrl+c will kill the container
