FROM ubuntu:16.04

WORKDIR /1.7
RUN apt-get update
RUN apt-get install curl -y

COPY curler.sh .
RUN chmod +x curler.sh
CMD ./curler.sh
