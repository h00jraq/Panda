FROM ubuntu:18.04
WORKDIR /home
RUN apt-get update && apt-get install curl openjdk-11-jdk git maven -y
RUN adduser --disabled-password --gecos "" jenkins
RUN curl -fsSL https://get.docker.com/ | sh
CMD ["/bin/sh"]
