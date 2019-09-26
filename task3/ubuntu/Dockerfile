FROM   ubuntu:latest
LABEL  maintainer="Talantbek Karmyshakov uchkunfan@gmail.com"
RUN    apt-get update && apt-get upgrade -y && apt-get install apache2 -y
EXPOSE 80
CMD    ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]

