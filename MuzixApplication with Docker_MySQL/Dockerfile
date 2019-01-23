FROM openjdk:11.0-jdk
ADD ./target/MuzixApplication-0.0.1-SNAPSHOT.jar /muzix/spring-boot-app/MuzixApplication-0.0.1-SNAPSHOT.jar
WORKDIR muzix/spring-boot-app
ENV MYSQL_DATABASE=MuzixDB
ENV MYSQL_PASSWORD=Root@123
EXPOSE 8084
ENTRYPOINT ["java", "-jar", "/muzix/spring-boot-app/MuzixApplication-0.0.1-SNAPSHOT.jar"]
