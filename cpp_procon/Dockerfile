FROM ubuntu:latest
WORKDIR /home/projects

RUN apt-get update && DEBIAN_FRONTEND="noninteractive" TZ="America/New_York" apt-get install -y tzdata && apt-get install -y vim build-essential cmake gdb git
RUN git clone https://github.com/atcoder/ac-library.git