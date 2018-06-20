FROM java:8
VOLUME /tmp
ADD ./target/eurekaServer!-0.0.1.jar /run.jar
RUN bash -c 'touch /run.jar'
EXPOSE 8761
ENTRYPOINT ["java","-jar","/run.jar"]