## Ubuntu Dockerfile

Ubuntu Dockerfile with essential tools and packages

### Base Docker Image

* [ubuntu:14.04](https://registry.hub.docker.com/u/library/ubuntu/)


### Installation
Execute either of the following:

    docker pull srdc/ubuntu:14.04 [latest]    [downloads the image from Docker Hub]
    docker build -t srdc/ubuntu:14.04 .       [builds from the local Dockerfile]


### Usage

    docker run -it --rm srdc/ubuntu
