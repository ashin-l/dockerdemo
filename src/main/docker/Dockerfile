FROM adoptopenjdk:11-jdk-openj9
VOLUME /tmp
ADD spring-boot-dockerdemo-1.0.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]