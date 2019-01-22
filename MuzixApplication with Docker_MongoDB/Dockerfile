FROM openjdk:11.0-jdk
ADD ./target/MuzixApplication-0.0.1-SNAPSHOT.jar /muzix/spring-boot-app/MuzixApplication-0.0.1-SNAPSHOT.jar
WORKDIR muzix/spring-boot-app
EXPOSE 8082
ENTRYPOINT ["java", "-jar", "MuzixApplication-0.0.1-SNAPSHOT.jar"]
