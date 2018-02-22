# This to build my apache
FROM ubuntu:latest
MAINTAINER Ravindrareddy84@gmail.com
RUN apt-get -y  update 
COPY config/packages /opt/packages
RUN apt-get -y install `cat /opt/packages`
EXPOSE 80
ADD code /var/www/html
CMD ["apachectl","-D","FOREGROUND"]

