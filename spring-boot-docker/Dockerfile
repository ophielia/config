FROM openjdk:8-jre-alpine
MAINTAINER margaret.martin@outlook.com
COPY target/config-server-1.0-SNAPSHOT.jar /opt/spring-cloud/lib/config-server.jar
ENTRYPOINT ["/usr/bin/java"]
CMD ["-jar", "/opt/spring-cloud/lib/config-server.jar"]
VOLUME /var/lib/spring-cloud/config-repo

