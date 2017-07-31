grpc
=======

```
syntax = "proto3";


// API service definitions

service rtpMediaServices {

rpc InitRequest(google.protobuf.Empty) returns (InitResponse) {}

rpc StatusRequest(google.protobuf.Empty) returns (StatusResponse) {}

rpc CreateChannel(CreateChannelRequest) returns (CreateChannelResponse){}

rpc UpdateChannel(UpdateChannelRequest) returns (google.protobuf.Empty){}

rpc DeleteChannel(DeleteChannelRequest) returns (google.protobuf.Empty){}


}
```
