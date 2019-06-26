Protocol Buffers - Google's data interchange format
Copyright 2008 Google Inc.
https://developers.google.com/protocol-buffers/

This package contains a precompiled binary version of the protocol buffer
compiler (protoc). This binary is intended for users who want to use Protocol
Buffers in languages other than C++ but do not want to compile protoc
themselves. To install, simply place this binary somewhere in your PATH.

If you intend to use the included well known types then don't forget to
copy the contents of the 'include' directory somewhere as well, for example
into '/usr/local/include/'.

Please refer to our official github site for more installation instructions:
  https://github.com/protocolbuffers/protobuf



# tutorial for golang
https://medium.com/@amsokol.com/tutorial-how-to-develop-go-grpc-microservice-with-http-rest-endpoint-middleware-kubernetes-daebb36a97e9

### breaf
download binary file and
``` bash

# install protobuf
brew install protobuf

# or copy bin file ro a $PATH dir
# https://github.com/protocolbuffers/protobuf/releases

wget -c https://github.com/protocolbuffers/protobuf/releases/download/v3.8.0/protoc-3.8.0-linux-x86_64.zip
```

install golang plugin for protobuf
``` bash
# install protoc-gen-go
go get -u github.com/golang/protobuf/{proto,protoc-gen-go}
```

generate go file from proto file
``` bash
./third_party/protoc-gen.sh
 ```