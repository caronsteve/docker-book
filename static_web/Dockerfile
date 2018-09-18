FROM ubuntu:16.04
MAINTAINER Steve Caron "caronsteve@yahoo.ca"
ENV VERSION 1.1 
RUN apt-get update; apt-get install -y nginx
RUN echo 'Hi, I am in your container dudessef' >/var/www/html/index.html
EXPOSE 80

