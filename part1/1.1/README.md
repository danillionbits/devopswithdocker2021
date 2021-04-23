sudo docker container run -d nginx
sudo docker container stop id1 id2
sudo docker ps -a

CONTAINER ID   IMAGE     COMMAND                  CREATED              STATUS                     PORTS     NAMES
e7cb9c54d9de   nginx     "/docker-entrypoint.…"   About a minute ago   Up About a minute          80/tcp    reverent_ellis
f0b56f441d82   nginx     "/docker-entrypoint.…"   2 minutes ago        Exited (0) 5 seconds ago             nice_mccarthy
d67207c89d91   nginx     "/docker-entrypoint.…"   2 minutes ago        Exited (0) 5 seconds ago             intelligent_lovelace

