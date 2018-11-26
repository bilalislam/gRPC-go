# gRPC-go
simple gRPC using with protocol buffer in go


# generate proto file in go service

```sh
$ protoc greet/greetpb/greet.proto  --go_out=plugins=grpc:.
```

# Sample usage for server.go

```sh
$ go run server.go
```

# Sample usage for clien.go

```sh
$ go run clien.go
```