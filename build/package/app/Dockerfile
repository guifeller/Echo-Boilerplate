FROM golang:1.20.1-alpine

WORKDIR /app

COPY ./ ./

RUN go install github.com/cosmtrek/air@latest

EXPOSE 8080

CMD ["air"]