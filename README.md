# docker_nginx_php
This is an example of working nginx server running in a separate container
with two different php versions running each in own container


edit hosts file (/etc/hosts on Linux) so that my_own_site.com redirects to localhost:
127.0.0.1 my_own_site.com

run docker-compose up
then go to localhost:8822. You will see that this case is handled by php7.4 version
then go to my_own_site.com. You will see that this case is handled by php7.2 version