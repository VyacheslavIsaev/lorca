FROM tomcat:9.0.30-jdk8-adoptopenjdk-openj9

# The path from_src must be relative to the Dockerfile's path
# ADD <from_src> <to_container>
ADD latest-grafana-kafka-rest-*.war /usr/local/tomcat/webapps/grafana-kafka-rest.war

EXPOSE 8080

CMD ["catalina.sh", "run"]