### grpcurl

**Description:** Interact with gRPC servers. <br />
Like `curl`, but for gRPC. <br />
**More information:** https://github.com/fullstorydev/grpcurl. <br />

Send an empty request:

```
grpcurl grpc.server.com:443 my.custom.server.Service/Method
```

Send a request with a header and a body:

```
grpcurl -H "Authorization: Bearer $token" -d '{"foo": "bar"}' grpc.server.com:443 my.custom.server.Service/Method
```

List all services exposed by a server:

```
grpcurl grpc.server.com:443 list
```

List all methods in a particular service:

```
grpcurl grpc.server.com:443 list my.custom.server.Service
```
