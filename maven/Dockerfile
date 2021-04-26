FROM ubuntu:16.04

RUN apt-get update
RUN apt-get install git -y
RUN apt-get install default-jdk -y
RUN apt-get install maven -y
RUN mkdir  /STS/Eclipse
RUN git clone https://github.com/shephertz/App42PaaS-Java-MySQL-Sample.git /STS/Eclipse
RUN cd /STS/Eclipse && mvn package

CMD ["/bin/bash"]
