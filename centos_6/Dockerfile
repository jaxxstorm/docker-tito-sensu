FROM centos:6

MAINTAINER Lee Briggs <lee@leebriggs.co.uk>

# Install deps
RUN yum update -y
RUN yum install -y ruby-devel gcc gcc-c++ wget curl libxml2 libxml2-devel libxslt-devel libxslt libyaml-devel libicu-devel openssl-devel expect git bzip2 make readline-devel rpm-devel

# Install sensu
RUN yum install -y http://repositories.sensuapp.org/yum/6/x86_64/sensu-0.21.0-2.x86_64.rpm

# Install tito
RUN yum install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-6.noarch.rpm # tito is in EPEL
RUN yum install -y tito
