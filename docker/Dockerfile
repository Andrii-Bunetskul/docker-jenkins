FROM nginx:latest

RUN rm /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/conf.d/default.conf
COPY index.nginx-debian.html /var/www/html/index.nginx-debian.html
COPY htpass /etc/nginx/htpass
