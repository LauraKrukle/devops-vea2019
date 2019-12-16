# Pull base image.
FROM ubuntu:latest

RUN \
# Update
apt-get update -y && \
# Install Java
apt-get install default-jre -y

ADD ./target/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar

EXPOSE 8081

CMD java -jar spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar