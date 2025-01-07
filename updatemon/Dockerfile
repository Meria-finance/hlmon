FROM golang:1.23.1-alpine3.20 AS runner

COPY ./go.mod /app/go.mod
COPY ./go.sum /app/go.sum
COPY ./main.go /app/main.go

WORKDIR /app

ENTRYPOINT [ "go", "run", "main.go" ]
