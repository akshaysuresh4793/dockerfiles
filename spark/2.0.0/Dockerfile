FROM centos:latest

# Some basic packages
RUN yum -y update
RUN yum install -y iproute initscripts openssh* wget vim nc telnet nmap mlocate tree gcc httpd php epel-release python-pip python-devel

# Java
RUN curl https://github.com/dminGod/install_scripts/blob/master/install_java.sh | bash

# Hadoop
RUN curl https://github.com/dminGod/install_scripts/blob/master/install_spark.sh | bash
