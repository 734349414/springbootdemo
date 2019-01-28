FROM 192.168.248.201:5000/centos_tomcat:latest
RUN rm -rf /usr/local/tomcat/webapps/springboot
COPY /var/lib/jenkins/workspace/springboot1/target/*.jar /usr/local/tomcat/webapps/springboothehe.jar
CMD ["catalina.sh", "run"]
