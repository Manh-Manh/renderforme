FROM openjdk:8

WORKDIR /apptest

RUN mkdir -p /apptest/upload
RUN mkdir -p /apptest/dowload

VOLUME /tmp
RUN chmod -R 777 /tmp

COPY PrintHello.jar /apptest


CMD ["java","-jar","PrintHello.jar"]

EXPOSE 8080/tcp