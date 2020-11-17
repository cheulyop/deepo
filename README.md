# Deepo

This Docker image is based on the [original Deepo image](https://github.com/ufoym/deepo) and provides an environment for quick and easy deep learning research. It uses `nvidia/cuda:10.2-cudnn8-devel-ubuntu18.04` as a base image (see [https://hub.docker.com/r/nvidia/cuda](https://hub.docker.com/r/nvidia/cuda)) and includes the following:
* Ubuntu 18.04
* CUDA 10.2 and cuDNN 8
* Python 3.8
* Pytorch (latest)
* TensorFlow (latest)
* ONNX (latest)

Anyone can freely reuse/modify this repository. However, I strongly recommend that you refer to the original Deepo documentation if you have questions or are interested in adding features.