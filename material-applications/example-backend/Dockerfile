FROM golang:1.16-alpine

WORKDIR /usr/src/app

COPY go.mod ./

COPY go.sum ./

COPY . .

RUN go build -o /server

EXPOSE 8080

CMD [ "/server" ]