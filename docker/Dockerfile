FROM tomcat:7-jre8

LABEL maintainer="ioexcept@gmail.com"
LABEL version="1.1"

COPY warrensburg.war /usr/local/tomcat/webapps/
COPY server.xml /usr/local/tomcat/conf/server.xml
RUN rm -rf webapps/ROOT
