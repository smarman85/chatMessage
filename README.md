# gRPC intro (concept)
source: https://tutorialedge.net/golang/go-grpc-beginners-tutorial/

# Run server:
```bash
$ go run server.go
Go gRPC Tutorial!
```

# Run client:
```bash
$ go run client.go
2021/05/29 10:00:36 Response from server: Hello From the Server!

response on server:
$ go run server.go
Go gRPC Tutorial!
2021/05/29 09:58:00 Receive message body from client: Hello From Client!
```

Look into:
 - `$ protoc --go_out=plugins=grpc:chat chat.proto` wouldn't build without adding `option go_package = "./";` to chat.proto
 - protocol buffers: https://tutorialedge.net/golang/go-protocol-buffer-tutorial/
