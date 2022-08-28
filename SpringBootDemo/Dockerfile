FROM openjdk:8
VOLUME /usr/local/tmp
WORKDIR /src
COPY ./target/study-1.0.jar /study-1.0.jar
ENTRYPOINT ["java","-jar","/study-1.0.jar"]
EXPOSE 8086