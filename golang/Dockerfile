FROM golang:1.6-alpine

WORKDIR /go/src/app

RUN go get -d -v ./...
RUN go install -v ./...

CMD ["go", "run", "main.go"]
