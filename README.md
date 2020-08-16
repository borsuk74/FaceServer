FaceServer

To generate python code from face.proto

$ pip install grpcio
$ pip install grpcio-tools

$ python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. face.proto
