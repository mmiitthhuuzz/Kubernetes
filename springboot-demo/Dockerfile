FROM openjdk:17-alpine
VOLUME /main-app
ADD target/kuber.jar kuber.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar","/kuber.jar"]