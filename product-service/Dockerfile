FROM openjdk:8-jdk-alpine

COPY ./build/libs/product-service-0.0.1-SNAPSHOT.jar /app/
COPY ./run.sh /app/
WORKDIR /app
EXPOSE 8081
CMD ["sh", "run.sh"]

