FROM golang:1.17.5-alpine3.15

LABEL author=charlie

RUN go env -w GO111MODULE=on  GOPROXY="https://goproxy.cn,direct"

WORKDIR /www
