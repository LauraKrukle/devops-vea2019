FROM java:8-jdk-alpine
#COPY spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar /target/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar
WORKDIR /target
#RUN chown -R admin:admin /target
RUN chmod -R 777 /target
EXPOSE 8081
ADD /target/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar
CMD java -jar spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar
#ENTRYPOINT ["java", "-jar", "/target/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar"]