FROM centos:centos7
RUN yum -y update && yum -y install bridge-utils wget which curl unzip openssl && yum -y clean all
RUN echo "root:atomic" | chpasswd