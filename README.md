# dockerfiles
### caffe-py3
Dockerfile of caffe with python3

forked from https://github.com/BVLC/caffe/tree/master/docker
#### gpu
```
$ cd caffe-py3-gpu
$ nvidia-docker build -t caffe-py3-gpu .
```
#### cpu
```
$ cd caffe-py3-cpu
$ docker build -t caffe-py3-cpu .
```

### PyTorch
Dockerfile of PyTorch on CPU

forked from https://github.com/pytorch/pytorch/blob/master/tools/docker/Dockerfile_runtime
#### cpu
```
$ cd pytorch-py3-cpu
$ docker build -t pytorch-py3-cpu .
```
