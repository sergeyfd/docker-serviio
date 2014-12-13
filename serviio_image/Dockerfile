FROM fedora:21
MAINTAINER Serge Dubrouski "sergeyfd@gmail.com"
RUN rpm -Uvh http://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-21.noarch.rpm
RUN yum -y install tar wget java ffmpeg librtmp
WORKDIR /opt
ENV REFRESH_AT 2014-12-12
RUN wget http://download.serviio.org/releases/serviio-1.4.1.2-linux.tar.gz
RUN tar xvzf serviio-1.4.1.2-linux.tar.gz; rm serviio-1.4.1.2-linux.tar.gz
RUN mv  serviio-1.4.1.2 serviio

ENTRYPOINT [ "ls", "serviio"]
