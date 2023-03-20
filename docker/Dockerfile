FROM java:8-jre-alpine

VOLUME /tmp

COPY ./target/discovery-1.0-SNAPSHOT.jar discovery-1.0-SNAPSHOT.jar

EXPOSE 8761

ENTRYPOINT ["java", "-jar", "./discovery-1.0-SNAPSHOT.jar"]