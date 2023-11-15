FROM ubuntu:18.04

RUN apt-get update && apt-get install -y curl && apt-get install -y wget && apt-get -y install git
RUN curl -O https://dl.google.com/go/go1.6.2.linux-amd64.tar.gz && tar xvf go1.6.2.linux-amd64.tar.gz && mv go /usr/local