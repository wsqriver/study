FROM openjdk:8
RUN ["echo $0"]
VOLUME /usr/local/tmp
COPY ./target/study-1.0.jar SpringBootDemo/study-1.0.jar
ENTRYPOINT ["java","-jar","/study-1.0.jar"]
EXPOSE 8086