FROM golang:1.14
WORKDIR /usr/src/app
COPY ./src/go .

RUN go get -d -v ./...
RUN go install -v ./...

EXPOSE 8080
CMD ["app"]