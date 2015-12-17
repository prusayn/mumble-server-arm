# Mumble server Dockerfile for ARM

This repository contains **Dockerfile** of [Mumble](http://wiki.mumble.info/wiki/Main_Page) for [Docker](https://www.docker.com/)'s [automated build](https://hub.docker.com/u/prusayn/mumble-server-arm/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).

## Base Docker Image

- [ubuntu armhf](https://hub.docker.com/r/ioft/armhf-ubuntu/)

## Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/prusayn/mumble-server-arm/) from public [Docker Hub Registry](https://hub.docker.com): `docker pull prusayn/mumble-server-arm`

## Usage

To launch it, just type:

```
docker run -d -p 64738:64738 prusayn/mumble-server-arm
```
