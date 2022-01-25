# Dockerfile
Pull base image

From tomcat:8-jre8
# Maintainer
MAINTAINER " rebeccalouisseul@hotmail.com"
COPY ./webapp/target/webapp.war /usr/local/tomcat/webapps
