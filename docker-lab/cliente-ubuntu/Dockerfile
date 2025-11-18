# Dockerfile correcto
FROM ubuntu:latest

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && \
    apt-get install -y curl wget dnsutils iputils-ping lynx net-tools && \
    rm -rf /var/lib/apt/lists/*

CMD ["bash"]
