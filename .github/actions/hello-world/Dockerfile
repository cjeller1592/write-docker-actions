FROM golang:1.5

WORKDIR /go/src/hello

COPY . .

RUN go get -d -v ./...

RUN go install -v ./...

CMD ["hello"]