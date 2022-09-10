FROM golang:1.17.8-alpine

EXPOSE 8080

RUN apk update && \
    apk add git

RUN mkdir /go/src/app

WORKDIR /go/src/app

ADD . /go/src/app