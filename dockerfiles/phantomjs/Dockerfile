FROM centos:7

RUN yum update -y \
  && yum install -y freetype fontconfig bzip2 wget java-1.6.0-openjdk \
  && mkdir /opt/phantomjs \
  && cd /opt/phantomjs \
  && wget https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-2.1.1-linux-x86_64.tar.bz2 \
  && tar xvf phantomjs-1.9.1-linux-i686.tar.bz2
