FROM tomcat:8.0
COPY /var/lib/jenkins/workspace/docker-ci-pipeline/java-tomcat-sample/target/**/*.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
