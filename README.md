# gRPChello

### generate code
protoc -I src/main/ src/main/hello.proto --go_out=plugins=grpc:hello
