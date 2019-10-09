# urop-2019Fall
pytorch

1.pybind11     
call c++
version:25abf7e
https://github.com/pybind/pybind11      

2.cub  :provide reusable software components for every layer of the CUDA programming model
used for CUDA
version:285aeeb
https://github.com/NVlabs/cub.git

3.eigen 
mathematic computation
version:d41dc4d
https://github.com/eigenteam/eigen-git-mirror.git

4．Google test: A merger of the formerly separate GoogleTest and GoogleMock projects.
for Google c++ test
version:2fe3bd9
https://github.com/google/googletest

5.benchmark: Benchmark code snippets 
for test(like Google test）
version:505be96
https://github.com/google/benchmark.git

6.protobuf:  Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data
Google's data interchange format
48cb18e
https://github.com/protocolbuffers/protobuf

7. ios-cmake
compil
8abaed6
https://github.com/Yangqing/ios-cmake

8.NNPACK: an acceleration package for neural network computations.
CNN computation
c039579
https://github.com/Maratyszcza/NNPACK.git

9.gloo: a collective communications library which contains a number of algorithms useful for machine learning.
machine learning algorithm
ca528e3
https://github.com/facebookincubator/gloo

10. pthreadpool: is a pthread-based thread pool implementation,
job schedule
13da0b4
https://github.com/Maratyszcza/pthreadpool.git

11.FXdiv division via fixed-point multiplication by inverse
mathematical computation
b742d11
https://github.com/Maratyszcza/FXdiv

12.FP16: conversion to/from half-precision floating point formats
mathematical computation
https://github.com/Maratyszcza/FP16

13.psimd: Portable 128-bit SIMD intrinsics
???
febbb1c
https://github.com/Maratyszcza/psimd

14.zstd：a fast lossless compression algorithm
compression algorithm
aec56a5
https://github.com/facebook/zstd.git

15. cpuinfo:  detect essential for performance optimization information about host CPU.
cpu detection
89fe169
https://github.com/pytorch/cpuinfo.git


16.enum34
python type
4cfedc4
https://github.com/PeachPy/enum34

17.peachpy: a python framework for writing high-performance assembly kernels.
assembly framework
07d8fde
https://github.com/Maratyszcza/PeachPy.git

18.six: It provides utility functions for smoothing over the differences between the Python versions with the goal of writing Python code that is compatible on both Python versions
write code for diff python version 
15e3143
https://github.com/benjaminp/six

19.ONNX:empower AI developers to choose the right tool as their project evolves.
Ai model
2891e14
https://github.com/onnx/onnx

20.sleef:  functions for evaluating some elementary functions are implemented. The library also includes DFT subroutines.
math computation
7f523de
https://github.com/shibatch/sleef

21.Ideep Chainer Backend for Intel Architecture, a Chainer module providing numpy like API and DNN acceleration using MKL-DNN
deep learning framework 
78eafa5
https://github.com/intel/ideep

22.nccl. A standard collective communication library
for gpu
no version
https://github.com/NVIDIA/nccl

23.gemmlowp. Do matrix computations.
mathematical computation
https://github.com/google/gemmlowp.git

24.qnnpack. mobile-optimized library for low-precision high-performance neural network inference
provide NN operation for framework
7d2a4e9
https://github.com/pytorch/QNNPACK

25.fbgemm. For matrix multiplication(Facebook)
Mathematical computation
266b453
https://github.com/pytorch/fbgemm

26.foxi:Onnxifi with Facebook extension
8f74bc4
https://github.com/houseroad/foxi.git

27.tbb. Help write parallel c++ programs
a51a90b
https://github.com/01org/tbb

28.fbjni. Facebook developed library.
Facebook
no version
https://github.com/IvanKobzarev/fbjni.git

pytorch classification:

1.Mathematical computation:
eigen,FXdiv,FP16,sleef,gemmlowp,fbgemm,

2.test
Google test,benchmark

3.compile
ios-cmake,peachpy

4.compression at zlib level
zstd

5.relate c++
pybind11,Google test,tbb

6.cpu,gpu
cub,NNPACK,cpuinfo

7.ML,Dl algorithm and model
gloo,ONNX,Ideep Chainer


Tensorflow（used by TF， compiled by bazel）
1.Fp16
"https://github.com/Maratyszcza/FP16/archive/febbb1c163726b5db24bed55cc9dc42529068997.tar.gz"

2.aws
"https://github.com/aws/aws-sdk-cpp/archive/1.5.8.tar.gz"

3.flatbuffer
"https://github.com/google/flatbuffers/archive/v1.11.0.tar.gz"

4.highwayhash
"https://github.com/google/highwayhash/archive/fd3d9af80465e4383162e4a7c5e2f406e82dd968.tar.gz"

5.hwloc
https://download.open-mpi.org/release/hwloc/v2.0/hwloc-2.0.3.tar.gz

6.icu. For Unicode processing
https://storage.googleapis.com/mirror.tensorflow.org/github.com
https://github.com/unicode-org/icu/archive/release-64-2.zip

7.jpeg. For image processing
https://github.com/libjpeg-turbo/libjpeg-turbo/archive/2.0.0.tar.gz

8.keras-application python package. :load keras package
https://storage.googleapis.com/mirror.tensorflow.org/github.com/keras-team/keras-applications/archive/1.0.8.tar.gz
https://github.com/keras-team/keras-applications/archive/1.0.8.tar.gz

9.kissfft
https://storage.googleapis.com/mirror.tensorflow.org/github.com/mborgerding/kissfft/archive/36dbc057604f00aacfc0288ddad57e3b21cfc1b8.tar.gz",
"https://github.com/mborgerding/kissfft/archive/36dbc057604f00aacfc0288ddad57e3b21cfc1b8.tar.gz

10.nasm
https://storage.googleapis.com/mirror.tensorflow.org/www.nasm.us/pub/nasm/releasebuilds/2.13.03/nasm-2.13.03.tar.bz2
http://www.nasm.us/pub/nasm/releasebuilds/2.13.03/nasm-2.13.03.tar.bz2

11.nccl,ngraph(not mentioned used by TF)

12.opencl-header
https://github.com/KhronosGroup/OpenCL-Headers/archive/0d5f18c6e7196863bc1557a693f1509adfcee056.tar.gz

13.ortools
https://storage.googleapis.com/mirror.tensorflow.org/github.com/google/or-tools/archive/v6.7.2.tar.gz
https://github.com/google/or-tools/archive/v6.7.2.tar.gz

14.pasta
https://storage.googleapis.com/mirror.tensorflow.org/github.com/google/pasta/archive/v0.1.2.tar.gz
https://github.com/google/pasta/archive/v0.1.2.tar.gz

