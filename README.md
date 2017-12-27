# TensorFlow RDMA version

**See more in `doc/rdma.pdf`**
<br/>
<br/>
by Kaixi from Unique Studio of Huazhong University of Science and Technology.

# Src

Distributed communication of tensorflow is in git submodule `gRpc`. All files modified are in grpc. when transfer grpc to rdma version, modify Bazel build file: grpc.BUILD to use grpc rdma version.

gRPC code:

```
git clone https://github.com/kaixili/Tensorflow-RDMA
git clone Tensorflow-RDMA/src/grpc.git
```
