FROM phpdockerio/nginx:latest
MAINTAINER Ronan Pozzi <contact@treenity-web.fr>

COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./conf.d/default.conf /etc/nginx/conf.d/

VOLUME ['/var/www/html']

WORKDIR ['/var/www/html']