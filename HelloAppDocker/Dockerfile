FROM tomcat:8.5.38-jre8-alpine

MAINTAINER John Doe "johndoe@email.com"

EXPOSE 8080

RUN rm -rf /usr/local/tomcat/webapps/*

COPY HelloApp.war /usr/local/tomcat/webapps/ROOT.war

CMD ["catalina.sh", "run"]
