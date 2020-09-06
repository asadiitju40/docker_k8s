FROM ubuntu:latest
WORKDIR /src
COPY http_server.py /src
RUN apt-get update
# Install vim
RUN apt install vim -y

# Install python 3.7
RUN apt install software-properties-common -y
RUN add-apt-repository ppa:deadsnakes/ppa
RUN apt install python3.8 -y

EXPOSE 8080
ENTRYPOINT ["/usr/bin/python3"]
CMD ["http_server.py"]