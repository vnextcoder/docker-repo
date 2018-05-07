FROM debian:jessie
MAINTAINER avinash barnwal <vnextcoder@gmail.com>
run apt-get -y update
run apt-get -y install apache2
VOLUME [ "/var/www/html" ]
WORKDIR /var/www/html
ADD index.html /var/www/html/index.html
CMD ["/usr/sbin/apache2ctl", "-D" , "FOREGROUND"]
EXPOSE 80
