FROM ubuntu:18.04

RUN apt-get update -y

RUN apt-get install apache2 -y

CMD ["apache2ctl", "-D", "FOREGROUND"]

EXPOSE 80
