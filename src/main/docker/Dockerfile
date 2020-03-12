FROM java:8-jdk-alpine
COPY ./target/lab-3-server-0.0.1-SNAPSHOT.jar /usr/app/

WORKDIR /usr/app
RUN sh -c 'touch lab-3-server-0.0.1-SNAPSHOT.jar'
ENTRYPOINT ["java","-jar","lab-3-server-0.0.1-SNAPSHOT.jar"]

