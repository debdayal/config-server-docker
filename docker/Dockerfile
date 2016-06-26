FROM java:8
VOLUME /tmp
EXPOSE 8888
ADD config-server-1.0.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
