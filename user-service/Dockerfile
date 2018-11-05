FROM openjdk:8-jdk-alpine

COPY ./build/libs/user-service-0.0.1-SNAPSHOT.jar /app/
COPY ./run.sh /app/
COPY ./run.sh /app/test/
WORKDIR /app
RUN mkdir /data100 && touch /data100/file100
VOLUME /data100
EXPOSE 8081
CMD ["sh", "run.sh"]

