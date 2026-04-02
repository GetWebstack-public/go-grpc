FROM golang:1.22-alpine
WORKDIR /app
RUN apk add --no-cache protobuf-dev
RUN go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.34.0 && \
    go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.3.0 && \
    go install github.com/air-verse/air@v1.52.3
COPY go.mod ./
RUN go mod download
COPY . .
RUN protoc --go_out=. --go_opt=paths=source_relative \
           --go-grpc_out=. --go-grpc_opt=paths=source_relative \
           api/service.proto
EXPOSE 50051
CMD ["air", "-c", ".air.toml"]
