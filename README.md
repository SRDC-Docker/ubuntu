### Ubuntu Dockerfiles

Ubuntu Dockerfiles based on (https://registry.hub.docker.com/u/library/ubuntu/)

### Docker Tags

* `latest` (default): Ubuntu 16.04 (alias to `16.04`)
* `16.04`: Ubuntu 16.04
* `14.04`: Ubuntu 14.04

### Installation
Execute either of the following:

    docker pull srdc/ubuntu:tag       [downloads the image from Docker Hub]
    docker build -t srdc/ubuntu:tag .  [builds from the local Dockerfile]

### Usage

    docker run -it --rm srdc/ubuntu:tag