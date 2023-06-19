FROM golang:alpine
WORKDIR $GOPATH/src/github.com/carltonj2000/go-mod-ex1/
COPY . .
RUN go install -v ./...
EXPOSE 8080
CMD ["go-mod-ex1"]
