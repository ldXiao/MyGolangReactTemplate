FROM golang:1.14.2
RUN mkdir /app
ADD . /app/
WORKDIR /app
RUN go mod download
RUN go build -o app ./...
CMD ["app/MyGolangReactTemplate"]