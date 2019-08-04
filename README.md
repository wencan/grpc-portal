# grpc-portal
A gRPC dynamic gateway that similar to [grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway/), but does not require generate code.

## planning
- Automatically discovery upstream services.
- Automatically forward request/response based on HTTP URL prefix or gRPC service name.
- Automatically conversion from restful request/response to gRPC request/response based on [proto annotation](https://cloud.google.com/endpoints/docs/grpc/transcoding). annotations is obtained by [gRPC reflection](https://github.com/grpc/grpc/blob/master/doc/server-reflection.md).
- Implement dynamic [gRPC reflection](https://github.com/grpc/grpc/blob/master/doc/server-reflection.md).
