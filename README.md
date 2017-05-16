### Requirements
* protoc version 3 compiler

### Build steps
```sh
:; go get -u github.com/golang/protobuf/{proto,protoc-gen-go}
:; go get -u google.golang.org/grpc

:; protoc --go_out=plugins=grpc:. *.proto
```
