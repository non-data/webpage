FROM centos:latest

RUN yum -y install httpd php
RUN systemctl enable httpd

ENTRYPOINT ["/sbin/init"]
