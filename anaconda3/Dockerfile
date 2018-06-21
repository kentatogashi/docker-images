FROM ubuntu:latest
MAINTAINER kentatogashi <togashik@example.com>

ENV PATH=/root/anaconda3/bin:$PATH
RUN apt update
RUN apt install -y build-essential wget
RUN wget https://repo.anaconda.com/archive/Anaconda3-5.2.0-Linux-x86_64.sh -O /anaconda3.sh
RUN /bin/bash /anaconda3.sh -b -p /root/anaconda3
