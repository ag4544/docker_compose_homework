FROM maven:3.6.1-jdk-8-alpine

# Install modules
RUN cd /root/ && git clone https://github.com/ag4544/boxfuse-sample.git && cd ./boxfuse-sample/ && mvn package
