# Docker Demo

## Cheat sheet

#### start nginx container
docker run --name nginx-me -p 8088:80 -d --rm -v /home/dockerdev/dockerdemo/me/html:/usr/share/nginx/html nginx

#### stop container
docker stop nginx-me

#### networking encasulation
docker run -it alpine ip addr show

docker run --net=host -it alpine ip addr show

#### process encapsulation
docker run -it alpine ps aux

docker run -it --pid=host alpine ps aux








