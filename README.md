# Emscripten Docker (Unofficial Image)
[![Build Status](https://jenkins.lollersk8r.eu/buildStatus/icon?job=public%2Femscripten-docker.release&style=flat-square)](https://jenkins.lollersk8r.eu/job/public/job/emscripten-docker.release/)

This repository contains source files for Docker Hub projects.

__If you're looking for readme related to specific DockerImages, please see following table where to look for a specific readme.__

## Docker Files and Images

| DockerHub | Dockerfile | Readme | Badges |
| --- | --- | --- | --- |
| [lollersk8r/emscripten-slim](https://hub.docker.com/r/lollersk8r/emscripten-slim/) | [Dockerfile](./docker/lollersk8r/emscripten-slim/Dockerfile) | [emscripten-slim.md](./docs/emscripten-slim.md) | [![Docker Pulls](https://img.shields.io/docker/pulls/lollersk8r/emscripten-slim.svg)](https://store.docker.com/community/images/lollersk8r/emscripten-slim/)<br/>[![Size](https://images.microbadger.com/badges/image/lollersk8r/emscripten-slim.svg)](https://microbadger.com/images/lollersk8r/emscripten-slim/)<br/>[![Sanity](https://badges.herokuapp.com/travis/lollersk8reu/emscripten-docker?env=IMAGE=lollersk8r/emscripten-slim&label=hello)](https://travis-ci.org/lollersk8reu/emscripten-docker) |
| [lollersk8r/emscripten](https://hub.docker.com/r/lollersk8r/emscripten/) | [Dockerfile](./docker/lollersk8r/emscripten/Dockerfile) | [emscripten.md](./docs/emscripten.md) | [![Docker Pulls](https://img.shields.io/docker/pulls/lollersk8r/emscripten.svg)](https://store.docker.com/community/images/lollersk8r/emscripten/)<br/>[![Size](https://images.microbadger.com/badges/image/lollersk8r/emscripten.svg)](https://microbadger.com/images/lollersk8r/emscripten/)<br/>[![Sanity](https://badges.herokuapp.com/travis/lollersk8reu/emscripten-docker?env=IMAGE=lollersk8r/emscripten&label=hello)](https://travis-ci.org/lollersk8reu/emscripten-docker) |
| [lollersk8r/emscripten-ubuntu](https://hub.docker.com/r/lollersk8r/emscripten-ubuntu/) | [Dockerfile](./docker/lollersk8r/emscripten-ubuntu/Dockerfile) | [emscripten-ubuntu.md](./docs/emscripten-ubuntu.md) | [![Docker Pulls](https://img.shields.io/docker/pulls/lollersk8r/emscripten-ubuntu.svg)](https://store.docker.com/community/images/lollersk8r/emscripten-ubuntu/)<br/>[![Size](https://images.microbadger.com/badges/image/lollersk8r/emscripten-ubuntu.svg)](https://microbadger.com/images/lollersk8r/emscripten-ubuntu/)<br/>[![Sanity](https://badges.herokuapp.com/travis/lollersk8reu/emscripten-docker?env=IMAGE=lollersk8r/emscripten-ubuntu&label=hello)](https://travis-ci.org/lollersk8reu/emscripten-docker) |
| [lollersk8r/emscripten-upstream](https://hub.docker.com/r/lollersk8r/emscripten-upstream/) | [Dockerfile](./docker/lollersk8r/emscripten-upstream/Dockerfile) | [emscripten-upstream.md](./docs/emscripten-upstream.md) | [![Docker Pulls](https://img.shields.io/docker/pulls/lollersk8r/emscripten-upstream.svg)](https://store.docker.com/community/images/lollersk8r/emscripten-upstream/)<br/>[![Size](https://images.microbadger.com/badges/image/lollersk8r/emscripten-upstream.svg)](https://microbadger.com/images/lollersk8r/emscripten-upstream/)<br/>[![Sanity](https://badges.herokuapp.com/travis/lollersk8reu/emscripten-docker?env=IMAGE=lollersk8r/emscripten-upstream&label=hello)](https://travis-ci.org/lollersk8reu/emscripten-docker) |
| [lollersk8r/emscripten-fastcomp](https://hub.docker.com/r/lollersk8r/emscripten-fastcomp/) | [Dockerfile](./docker/lollersk8r/emscripten-fastcomp/Dockerfile) | [emscripten-fastcomp.md](./docs/emscripten-fastcomp.md) | [![Docker Pulls](https://img.shields.io/docker/pulls/lollersk8r/emscripten-fastcomp.svg)](https://store.docker.com/community/images/lollersk8r/emscripten-fastcomp/)<br/>[![Size](https://images.microbadger.com/badges/image/lollersk8r/emscripten-fastcomp.svg)](https://microbadger.com/images/lollersk8r/emscripten-fastcomp/)<br/>[![Sanity](https://badges.herokuapp.com/travis/lollersk8reu/emscripten-docker?env=IMAGE=lollersk8r/emscripten-fastcomp&label=hello)](https://travis-ci.org/lollersk8reu/emscripten-docker) |



## Usage of build script
```
➜ python3 -m builder --help
usage: __main__.py [-h] {compile,push,set_latest} ...

Emscripten Image generator

optional arguments:
  -h, --help            show this help message and exit

command:
  {compile,push,set_latest}
                        Main work command
    compile             Compile Docker images.
    push                Runs a service what will push created images
    set_latest          Automatically sets the 'latest' tag
```

## Who uses this image?

* https://github.com/medialize/sass.js
* https://github.com/jasoncharnes/run.rb
* https://github.com/GoogleChromeLabs/webm-wasm
* https://github.com/google/neuroglancer
* https://github.com/finos/perspective
* https://blog.qt.io/blog/2019/03/05/using-docker-test-qt-webassembly/
* https://docs.opencv.org/master/d4/da1/tutorial_js_setup.html
* https://github.com/kalwalt/jsartoolkitNFT
* https://github.com/iPlug2/iPlug2/wiki/Build-a-WAM-project-using-Emscripten-and-Docker
* And many more that I'm proud of each!


## License
[![MIT](https://img.shields.io/github/license/lollersk8reu/emscripten-docker.svg?style=flat-square)](https://github.com/lollersk8reu/emscripten-docker/blob/master/LICENSE)

