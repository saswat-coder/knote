FROM adoptopenjdk/openjdk8
WORKDIR /opt
ENV PORT 8080
EXPOSE 8080
COPY target/knote-java-1.0.0.jar /opt/app.jar
ENTRYPOINT exec java $JAVA_OPTS -jar app.jar