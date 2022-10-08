FROM ubuntu:18.04

RUN apt-get update

RUN apt-get install -y git


FROM httpd:2.4 
COPY index.html /usr/local/apache2/htdocs/
EXPOSE 80
