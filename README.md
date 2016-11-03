# nginx Docker

Starting the container:
$ docker run -d -p 80:80 -p 443:443 -v nginx_config:/etc/nginx --name my_nginx secops/nginx
