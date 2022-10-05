From openjdk:11
ARG JAR_FILE=target/*.JAR_FILE
COPY ${JAR_FILE} user-service.JAR_FILE
ENTRYPOINT ["java","-jar","/user-service.jar"]
EXPOSE 9002