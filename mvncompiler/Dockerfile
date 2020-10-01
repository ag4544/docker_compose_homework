FROM maven:3.6.3-jdk-11
RUN cd /root/ && git clone https://github.com/ag4544/boxfuse-sample.git && cd ./boxfuse-sample/ && mvn package
CMD ["ping", "localhost"]
ENTRYPOINT ["ping", "localhost"]