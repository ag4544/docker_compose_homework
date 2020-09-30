FROM maven:3.6.3-openjdk-14-slim
RUN apt install git
RUN cd /root/ && git clone https://github.com/ag4544/boxfuse-sample.git && cd ./boxfuse-sample/ && mvn package
