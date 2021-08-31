FROM devopsedu/webapp:latest
COPY website /var/www/html
RUN yum update && yum install php -y
CMD /usr/sbin/apachectl -D FOREGROUND
