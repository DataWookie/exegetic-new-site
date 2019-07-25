---
title: "Docker"
topic: true
subjects: ['Docker']
draft: false
intro: |
  Docker is a tool for creating, deploying and running applications using containers. A container encapsulates a complete execution environment. As a result the container can be run on any hardware or operating system that supports Docker.

  This course will teach you everything that you need to know to start using Docker.
duration: 2 days
requirements: |
  - Follow [these instructions](https://docs.docker.com/install/) to install Docker.
  - Create accounts on the following services:
    - [AWS](http://aws.amazon.com/) and
    - [Docker Hub](https://hub.docker.com/).
  - The [UNIX Essentials]({{< ref "unix-essentials.md" >}}) course is useful for understanding some of the details of a Dockerfile.
---

<!--
https://docs.docker.com/get-started/
https://thenewstack.io/understanding-the-docker-cache-for-faster-builds/
https://docker-curriculum.com/
https://medium.freecodecamp.org/a-beginner-friendly-introduction-to-containers-vms-and-docker-79a9e3e119b
-->

### Day 1

- What is Docker?
    - Virtualisation
    - Docker versus VMWare and VirtualBox
    - Images and Containers
    - Daemon and Client
- Using Images
    - Hello World - `busybox`
    - `docker pull` - fetch images
    - `docker images` - list fetched images
    - `docker run` - create a container
        - Naming a container (`--name`)
        - Handling cleanup (`--rm`)
        - Detach (`--detach`)
    - `docker logs` - output from containers
    - `docker ps` - list running containers
    - `docker stop` - stop running containers
    - `docker rm` - delete stopped containers
    - `docker rmi` - delete images we no longer need
- Writing a Dockerfile
    - Layers and the Union File System
    - `FROM` - Specifying the base image
    - Tags
    - `COPY` - Copying things to the image
    - `ADD` - Another way to get stuff onto the image
    - `RUN` - Executing processes on the image
        - Using `apt` to add software
        - Asserting non-interactive mode
    - `USER` - Which user?
    - `WORKDIR` - Setting the working directory
    - `EXPOSE` - What ports are available?
    - `CMD` - What will the image be running?
- Building an Image
    - `docker build` - build an image
    - Caching
    - Cleaning up temporary files
    - The build context and `.dockerignore`

### Day 2

- Dockerfile Revisited
    - Best practices
    - `ENV` - Default values for environment variables
- Debugging
    - Getting "inside" an image
    - `docker exec`
    - `docker attach`
- Volumes
    - Sharing data
    - Volumes on the host
    - Named volumes
- Networking
    - `docker network`
    - Network drivers
    - Bridge, Overlay and Host network
- Sharing Images
    - [Docker Hub](https://hub.docker.com/)
    - Docker Registry
    - `docker push` - publishing images
    - `docker search` - finding images
- Deploying
- Compose
    - Running multiple containers
    - Compose file syntax
    - Ports, volumes and links
    - Commands and flags
- Swarm
    - Distributing containers
    - Setup
    - Deploying application on a cluster

{{< comment >}}
- Kubernetes
    - Introduction

- Projects
    - Django/MySQL application using Docker Compose
{{< /comment >}}

<!--
- Projects
    - Static website
    - Dynamic webapp
-->