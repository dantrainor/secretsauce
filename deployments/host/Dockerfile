FROM centos/7
MAINTAINER http://www.centos.org
LABEL Vendor="CentOS"
LABEL License=GPLv2

COPY docker-network /etc/sysconfig/
RUN systemctl restart docker

RUN yum -y update && yum clean all
RUN yum -y install httpd bzip2 && yum clean all


