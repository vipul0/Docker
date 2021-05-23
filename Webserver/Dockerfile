FROM Centos:latest

Label "server"="Apache Webserver"

MAINTAINER Vipul Jain

RUN yum install httpd -y

COPY index.html /var/www/html/

CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]

EXPOSE 80
