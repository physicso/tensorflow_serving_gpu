# Motivation

There exists few documentation introducing TensorFlow Serving Docker configuration with GPU support. Hope this repo will benefit people who are struggling deploying TensorFlow Serving in their production environment with GPU servers.

# Method

The Dockerfile mainly comes from the official repo of TensorFlow Serving:

https://github.com/tensorflow/serving/blob/master/tensorflow_serving/tools/docker/Dockerfile.devel-gpu

It needs to be noted that one modification needs to be done:

`ENV BAZEL_VERSION 0.5.4`

# Note

Please refer to the built image on Docker Hub:

https://hub.docker.com/r/physicso/tf_serving_gpu/

Hope you enjoy this docker image :)
