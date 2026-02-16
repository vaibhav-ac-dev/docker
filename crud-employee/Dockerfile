FROM mcr.microsoft.com/openjdk/jdk:21-ubuntu

WORKDIR /app

COPY build/libs/crud-employee-0.0.1-SNAPSHOT.jar crud-employee.jar

EXPOSE 9090

ENTRYPOINT ["java", "-jar", "crud-employee.jar"]