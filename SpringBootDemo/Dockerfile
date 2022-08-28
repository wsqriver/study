FROM openjdk:8
WORKDIR /SpringBootDemo
RUN pwd
VOLUME /usr/local/tmp
COPY ./target/study-1.0.jar /study-1.0.jar
ENTRYPOINT ["java","-jar","/study-1.0.jar"]
EXPOSE 8086