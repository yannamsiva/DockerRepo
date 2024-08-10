FROM openjdk:17
MAINTAINER "shiva<21280>"
COPY target/WelcomeSbDeploy.jar /usr/app/
WORKDIR /usr/app/
EXPOSE 8080
ENTRYPOINT [ "java", "-jar","WelcomeSbDeploy.jar" ]