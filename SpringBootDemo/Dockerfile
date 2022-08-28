FROM openjdk:8
VOLUME /usr/local/tmp
WORKDIR /var/jenkins_home/workspace/springbootdemo/SpringBootDemo/target
COPY ["/study-1.0.jar", "/study-1.0.jar"]
ENTRYPOINT ["java","-jar","/study-1.0.jar"]
EXPOSE 8086