FROM openjdk:17-jdk-alpine

WORKDIR /app
ARG JAR_FILE=utilitybill/target/*.jar
COPY ${JAR_FILE} app.jar

ENTRYPOINT ["java","-jar","/app/app.jar","in.artamonov.utilitybill.UtilityBillApplication"]