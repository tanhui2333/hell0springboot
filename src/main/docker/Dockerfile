FROM openjdk:8-jre
VOLUME /tmp
ADD hell0-spring-boot.jar app.jar

EXPOSE 9090
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-Dspring.profiles.active=docker"]
CMD ["-jar","/app.jar"]
