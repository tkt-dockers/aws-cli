FROM ubuntu:bionic

LABEL maintainer="tktcorporation <tktcorporation@gmail.com>"

RUN apt-get update && apt-get -y upgrade
RUN apt-get install -y sudo curl unzip jq less git

RUN curl "https://d1vvhvl2y92vvt.cloudfront.net/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
RUN unzip awscliv2.zip
RUN ./aws/install
RUN rm awscliv2.zip