FROM maven:3.6.3-jdk-11
RUN cd /root/ && git clone https://github.com/ag4544/boxfuse-sample.git && cd ./boxfuse-sample/ && mvn package
RUN apt-get install nginx -y
CMD ["nginx", "-g", "daemon off;"]