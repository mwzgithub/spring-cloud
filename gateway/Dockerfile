FROM java:8-jdk-alpine

COPY ./target/gateway-1.0.0.jar /usr/app/

WORKDIR /usr/app

RUN sh -c 'touch gateway-1.0.0.jar'

ENTRYPOINT ["java", "-jar", "gateway-1.0.0.jar"]
