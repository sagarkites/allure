FROM debian
MAINTAINER anand_karri
RUN apt-get update -y
RUN apt-get install -y --no-install-recommends \
        openjdk-11-jre
RUN apt-get install wget -y && apt-get install unzip -y
COPY ./allure-commandline-2.13.6.zip /root
RUN unzip /root/allure-commandline-2.13.6.zip
WORKDIR /allure-2.13.6/bin
