# TensorFlow RDMA version

**See more in doc/rdma.pdf**
<br/>
<br/>
by Unique Studio of Huazhong University of Science and Technology.


# SRC

Distributed communication of tensorflow is in git submodule grpc. All files i modify is in grpc. when you transfer grpc to rdma version, you can modify Bazel build file: grpc.BUILD to use grpc rdma version.

gRPC code:

```
git clone https://github.com/kaixili/Tensorflow-RDMA
git clone Tensorflow-RDMA/src/grpc.git
```
