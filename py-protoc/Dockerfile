FROM python:3.8.0-alpine3.10

RUN apk add build-base \
 && pip install cython \
 && pip install grpcio-tools

WORKDIR /src
