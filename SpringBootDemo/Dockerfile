FROM openjdk:8
RUN echo $0
VOLUME /usr/local/tmp
COPY /var/jenkins_home/workspace/springbootdemo/SpringBootDemo/target/study-1.0.jar /var/jenkins_home/workspace/springbootdemo/SpringBootDemo/study-1.0.jar
ENTRYPOINT ["java","-jar","/var/jenkins_home/workspace/springbootdemo/SpringBootDemo/study-1.0.jar"]
EXPOSE 8086