FROM ubuntu:22.04

ARG ANSIBLE_VERSION

RUN apt update && apt install python3-pip -y && \
    rm -rf /var/lib/apt/lists/* && \
    apt clean && \
    pip install ansible==${ANSIBLE_VERSION}