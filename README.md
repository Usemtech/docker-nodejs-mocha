## Important note:

All the credit goes to [DigitallySeamless](https://github.com/DigitallySeamless). You can think of this repos as `copy/past/replace`
with small adjustments of the wonderful repos [docker-nodejs-bower-grunt](https://github.com/DigitallySeamless/docker-nodejs-bower-grunt).

## Docker with Node.js & Mocha
[![dockeri.co](http://dockeri.co/image/usemtech/nodejs-mocha)](https://hub.docker.com/r/usemtech/nodejs-mocha/)

This repository contains a **Dockerfile** of [Node.js](http://nodejs.org/) w/ [Mocha](https://mochajs.org/) for [automated tests](https://hub.docker.com/r/usemtech/nodejs-mocha/) published to the public [Docker Hub Registry](https://hub.docker.com/).

### Base Docker Image

* [library/node](https://hub.docker.com/r/library/node/)

### Supported tags and respective `Dockerfile` links
* [`0.8`](https://github.com/Usemtech/docker-nodejs-mocha/blob/v0.8/Dockerfile)
* [`0.8-onbuild`](https://github.com/Usemtech/docker-nodejs-mocha/blob/v0.8-onbuild/Dockerfile)
* [`0.10`](https://github.com/Usemtech/docker-nodejs-mocha/blob/v0.10/Dockerfile)
* [`0.10-onbuild`](https://github.com/Usemtech/docker-nodejs-mocha/blob/v0.10-onbuild/Dockerfile)
* [`0.12`](https://github.com/Usemtech/docker-nodejs-mocha/blob/v0.12/Dockerfile)
* [`0.12-onbuild`](https://github.com/Usemtech/docker-nodejs-mocha/blob/v0.12-onbuild/Dockerfile)
* [`4`](https://github.com/Usemtech/docker-nodejs-mocha/blob/v4/Dockerfile)
* [`4-onbuild`](https://github.com/Usemtech/docker-nodejs-mocha/blob/v4-onbuild/Dockerfile)
* [`5`](https://github.com/Usemtech/docker-nodejs-mocha/blob/v5/Dockerfile)
* [`5-onbuild`](https://github.com/Usemtech/docker-nodejs-mocha/blob/v5-onbuild/Dockerfile)
* [`latest`](https://github.com/Usemtech/docker-nodejs-mocha/blob/master/Dockerfile)
* [`onbuild`](https://github.com/Usemtech/docker-nodejs-mocha/blob/onbuild/Dockerfile)

### Installation

1. Install [Docker](https://www.docker.com/).

2. Download an [automated build](https://hub.docker.com/r/usemtech/nodejs-mocha/) from public the [Docker Hub Registry](https://hub.docker.com/): `docker pull usemtech/nodejs-mocha`

   (alternatively, you can build an image directly from this repository: `docker build -t="usemtech/nodejs-mocha" github.com/usemtech/nodejs-mocha`)


### Usage

    docker run -it --rm usemtech/nodejs-mocha

#### Run `node`

    docker run -it --rm usemtech/nodejs-mocha node

#### Run `npm`

    docker run -it --rm usemtech/nodejs-mocha npm

#### Run `mocha`

    docker run -it --rm usemtech/nodejs-mocha mocha

