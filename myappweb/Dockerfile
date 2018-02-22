# This to build my ubuntu apache
FROM ubuntu:latest
MAINTAINER Ravindrareddy84@gmail.com
RUN  apt-get update
RUN  apt-get install apache2 php5.6-mysql
EXPOSE 80
ADD code /var/www/html
CMD ["/usr/sbin/apache2ctl","-D","FOREGROUND"]

