# urop-2019Fall
pytorch (latest:1.2.0)
latest master -> 1.2.0 -> 1.1.0 -> 1.0.1 -> 1.0.0 -> 1.0rc1 -> 1.0rc0 -> 0.4.1 -> 0.4.0

1.pybind11     
call c++
version:    25abf7e(latest)
-> 5c8746f(v1.0.1) ->  add56cc(v0.4.1) 
https://github.com/pybind/pybind11      

2.cub  :provide reusable software components for every layer of the CUDA programming model
used for CUDA
version:285aeeb(all versions)

https://github.com/NVlabs/cub.git

3.eigen 
mathematic computation
version:d41dc4d(v1.2.0)
-> b8fa8f5(v1.1.0) -> f59336c(v1.0.1) -> cafae68(v1.0rc1) -> e9e9548(v0.4.1) -> 5a0ab9f(v0.4.0)
https://github.com/eigenteam/eigen-git-mirror.git

4．Google test: A merger of the formerly separate GoogleTest and GoogleMock projects.
for Google c++ test
version:2fe3bd9(v1.2.0)
-> 69e48e9(v0.4.1)
https://github.com/google/googletest

5.benchmark: Benchmark code snippets 
for test(like Google test）
version:505be96(v1.2.0)
-> 491360b(v0.4.0)
https://github.com/google/benchmark.git

6.protobuf:  Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data
Google's data interchange format
version: 48cb18e(v1.2.0)
-> 2761122(v1.0.1) 
https://github.com/protocolbuffers/protobuf

7. ios-cmake
compil
version: 8abaed6(v1.2.0)(all versions)

https://github.com/Yangqing/ios-cmake

8.NNPACK: an acceleration package for neural network computations.
CNN computation
version: c039579(v1.2.0)
-> 1e005b0(v1.0.1) -> af40ea7(v1.0rc1) -> 3eb0d45(v0.4.1) -> b63fe1b(v0.4.0)
https://github.com/Maratyszcza/NNPACK.git

9.gloo: a collective communications library which contains a number of algorithms useful for machine learning.
machine learning algorithm
version:ca528e3(latest)
-> 46ae6ec(v1.2.0) -> 670b4d4(v1.1.0) -> cdeb59d(v1.0.0) -> aa0d2e3(v1.0rc1) -> 69eef74(v0.4.1) -> aad0002(v0.4.0)

https://github.com/facebookincubator/gloo

10. pthreadpool: is a pthread-based thread pool implementation,
job schedule
version: 13da0b4(latest)
-> 2b06b31(v1.0rv1)
https://github.com/Maratyszcza/pthreadpool.git

11.FXdiv division via fixed-point multiplication by inverse
mathematical computation
version: b742d11(latest)
-> 811b482(v1.0rc1) 
https://github.com/Maratyszcza/FXdiv

12.FP16: conversion to/from half-precision floating point formats
mathematical computation
version:febbb1c(latest)
-> 34d4bf0(v1.0.1) -> 4b37bd3(v1.0rc1) -> 43d6d17(v0.4.1)
https://github.com/Maratyszcza/FP16

13.psimd: Portable 128-bit SIMD intrinsics
???
version: 90a938f(latest)
-> 4ac61b1(v1.0rc1)
https://github.com/Maratyszcza/psimd

14.zstd：a fast lossless compression algorithm
compression algorithm
version: aec56a5(all versions)
https://github.com/facebook/zstd.git

15. cpuinfo:  detect essential for performance optimization information about host CPU.
cpu detection
version:89fe169(latest)
-> c342292(v1.0.0) -> 4e8f043(v1.0rc1) -> 1e6c8c9(v0.4.1) -> 831dc28(v0.4.0)
https://github.com/pytorch/cpuinfo.git


16.python-enum34
python type
version: 4cfedc4(all versions)
https://github.com/PeachPy/enum34

17.python-peachpy: a python framework for writing high-performance assembly kernels.
assembly framework
version: 07d8fde(all versions)
https://github.com/Maratyszcza/PeachPy.git

18.python-six: It provides utility functions for smoothing over the differences between the Python versions with the goal of writing Python code that is compatible on both Python versions
write code for diff python version 
version: 15e3143(all version)
https://github.com/benjaminp/six

19.ONNX:empower AI developers to choose the right tool as their project evolves.
Ai model
version: 2891e14(latest version)
-> 28ca699(v1.2.0) -> 22662bf(v1.1.0) -> 4280470(v1.0.1) -> c4734c6(v1.0rc1) -> b2817a6(v0.4.1) -> 7e1bed5(v0.4.0)
https://github.com/onnx/onnx

20.sleef:  functions for evaluating some elementary functions are implemented. The library also includes DFT subroutines.
math computation
version:7f523de(latest version)
-> 9b249c5(v1.2.0) -> 191f655(v1.1.0) -> 6ff7a13(v1.0.1 until v0.4.1)  v0.4.0 hasn't sleef 
https://github.com/shibatch/sleef

21.Ideep :Chainer Backend for Intel Architecture, a Chainer module providing numpy like API and DNN acceleration using MKL-DNN
deep learning framework 
version: 78eafa5(latest version)
-> 0316184 (v1.2.0) -> 3a98675(v1.1.0) -> 7b8f9d0(v1.0.1) -> dedff8f(v1.0.0) -> 4bd9a68(v0.4.1) v0.4.0 hasn't Ideep
https://github.com/intel/ideep

22.nccl. A standard collective communication library
for gpu
version: 7c72dee(latest version)
-> 1450d42(v1.1.0) -> 3c6e252(v1.0.1)  cannot see previous version ID 
https://github.com/NVIDIA/nccl

23.gemmlowp. Do matrix computations.
mathematical computation
version: 3fb5c17(latest version)
-> 8416bab(v1.1.0)  first appear in v1.0.0
https://github.com/google/gemmlowp.git

24.qnnpack. mobile-optimized library for low-precision high-performance neural network inference
provide NN operation for framework
7d2a4e9(latest version)
-> 6c62fdd(v1.2.0) ->ef05e87(v1.0.1)  first appear in v1.0.0
https://github.com/pytorch/QNNPACK

25.fbgemm. For matrix multiplication(Facebook)
Mathematical computation
version:266b453(latest version)
-> f712cb2(v1.2.0) ->6ec218e(v1.1.0) -> 7933330(v1.0.1) -> 0d5a159(v1.0.0)   first appear in v1.0.0
https://github.com/pytorch/fbgemm

26.foxi:Onnxifi with Facebook extension
version: 8f74bc4(latest version ----  v1.1.0)
https://github.com/houseroad/foxi.git

27.tbb. Help write parallel c++ programs
version: a51a90b(latest version ----- v1.2.0)
https://github.com/01org/tbb



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

