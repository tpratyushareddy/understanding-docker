FROM fedora:latest

RUN yum install python3 -y
RUN yum install git -y
RUN git clone https://github.com/tpratyushareddy/understanding-docker.git

WORKDIR /understanding-docker/addition


ENTRYPOINT ["python", "add.py"]

