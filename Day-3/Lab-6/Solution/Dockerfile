FROM ubuntu:16.04
MAINTAINER Mayank Sachan "mayank.sachan@koenig-solutions.com"
RUN apt-get update 
RUN apt-get -y install nginx
RUN mkdir -p /var/www/html
ADD global.conf /etc/nginx/conf.d/
ADD nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
