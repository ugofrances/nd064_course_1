FROM golang:alpine
WORKDIR /go/src/app
ADD . .
RUN ls
RUN go mod init
RUN go build -o helloworld
EXPOSE 6111
ENTRYPOINT ["./helloworld"]