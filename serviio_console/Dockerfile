FROM sergeyfd/serviio_server:latest
MAINTAINER Serge Dubrouski "sergeyfd@gmail.com"
WORKDIR /opt
ENV REFRESH_AT 2014-12-12

#VOLUME /opt/serviio/log
#VOLUME /opt/serviio/library

#EXPOSE 8895/tcp 1900/udp 23423/tcp 23424/tcp

ENTRYPOINT [ "serviio/bin/serviio-console.sh" ]
