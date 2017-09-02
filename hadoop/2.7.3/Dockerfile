FROM centos:latest

# Some basic packages
RUN yum -y update
RUN yum install -y iproute initscripts openssh* wget vim nc telnet nmap mlocate tree gcc httpd php

# Java
RUN curl https://github.com/dminGod/install_scripts/blob/master/install_java.sh | bash

# Hadoop
RUN curl https://github.com/dminGod/install_scripts/blob/master/install_hadoop.sh | bash
