FROM openjdk:11.0.2-jre-slim

EXPOSE 8080

COPY . /usr/bin/app
WORKDIR /usr/bin/app

CMD ["java", "-jar", "api-gateway-0.0.1-SNAPSHOT.jar"]
# docker build -t cs3219/api-gateway:1.0.0 ./api-gateway