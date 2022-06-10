FROM tomcat:latest

LABEL maintainer="Antoni Xavier"

ADD ./docker/LocalCritic.war /usr/local/tomcat/webapps/

EXPOSE 8080

CMD ["catalina.sh", "run"]
