FROM python:latest

COPY ./infra /app
WORKDIR /app

# install the latest nodejs & npm
RUN apt update \
    && apt install -y nodejs npm \
    && apt clean

RUN npm install -g aws-cdk \
    && pip3 install --upgrade aws-cdk.core

RUN pip3 install awscli --upgrade
