FROM debian:latest

MAINTAINER Sergey Zolotaryow<zolotaryow.mswebdev@outlook.com>


RUN apt update && apt upgrade -y && apt install python3 git -y && python3 --version \
	&& git clone https://github.com/boy-hack/w9scan.git && cd w9scan \
	&& chmod +x w9scan.py

