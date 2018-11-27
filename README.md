# gRPC-go
simple gRPC using with protocol buffer in go

# Messaging Concepts
1. Unary
2. Server Streaming
3. Client Streaming
4. Bi Directional Streaming

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
$ go run client.go
```

Notes: Evans cli ref by https://github.com/ktr0731/evans
for the connect on cli 
