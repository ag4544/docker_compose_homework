FROM maven:3.6.3-jdk-11
RUN cd /root/ && git clone https://github.com/ag4544/boxfuse-sample.git && cd ./boxfuse-sample/ && mvn package
RUN mkdir /root/result/ && cp /root/boxfuse-sample/target/hello-1.0.war /root/result/ROOT.war
CMD ["ping", "127.0.0.1"]