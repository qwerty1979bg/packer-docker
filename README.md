# Packer template to create a docker image

This repository contains a Packer template for building a docker image

## Usage

1. [Install Packer](https://www.packer.io/intro/getting-started/install.html#precompiled-binaries)
2. [Install Docker](https://docs.docker.com/install/#supported-platforms)
3. Clone this repository `git clone https://github.com/qwerty1979bg/packer-docker`
4. Change directory `cd packer-docker`

4. Run the following:

```
$ export DOCKER_HUB_USERNAME=<Your Docker HUB username>
$ export DOCKER_HUB_PASSWORD=<Your Docker HUB password>
$ packer build docker.json
```

5. The image should be pushed to the Docker HUB

## To use the box with Docker Hub:

```
$ docker pull <USERNAME>/<TAG>
```
