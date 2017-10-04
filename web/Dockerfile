FROM centos:latest

RUN yum -y install httpd php
RUN systemctl enable httpd

RUN mv /var/www/html /var/www/html.a
RUN ln -s /var/myweb/html /var/www/html

ENTRYPOINT ["/sbin/init"]
