FROM maven:3.6.3-openjdk-14-slim
WORKDIR /root/
RUN  wget https://github.com/ag4544/boxfuse-sample/archive/master.zip && unzip master.zip && cd ./boxfuse-sample-master/ && mvn package
