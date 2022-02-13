# golang-grpc-service

### How to Generate
```
protoc --proto_path=. --go_out=./gen --go-grpc_out=./gen ./*.proto
```