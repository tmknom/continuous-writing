# continuous-writing

[![CircleCI](https://circleci.com/gh/tmknom/continuous-writing.svg?style=svg)](https://circleci.com/gh/tmknom/continuous-writing)
[![Docker Build Status](https://img.shields.io/docker/cloud/build/tmknom/continuous-writing.svg)](https://hub.docker.com/r/tmknom/continuous-writing/builds/)
[![Docker Automated build](https://img.shields.io/docker/cloud/automated/tmknom/continuous-writing.svg)](https://hub.docker.com/r/tmknom/continuous-writing/)
[![MicroBadger Size](https://img.shields.io/microbadger/image-size/tmknom/continuous-writing.svg)](https://microbadger.com/images/tmknom/continuous-writing)
[![MicroBadger Layers](https://img.shields.io/microbadger/layers/tmknom/continuous-writing.svg)](https://microbadger.com/images/tmknom/continuous-writing)
[![License](https://img.shields.io/github/license/tmknom/continuous-writing.svg)](https://opensource.org/licenses/Apache-2.0)

Dockerfile template.

## Requirements

- [Docker](https://www.docker.com/)

## Usage

```sh
curl -fsSL https://raw.githubusercontent.com/tmknom/continuous-writing/master/install | sh -s example
cd example
```

## Makefile targets

```text
build                          Build docker image
format                         Format code
help                           Show help
install                        Install requirements
lint                           Lint code
```

## Development

### Installation

```shell
git clone git@github.com:tmknom/continuous-writing.git
cd continuous-writing
make install
```

### Deployment

Automatically deployed by "[DockerHub Automated Build](https://docs.docker.com/docker-hub/builds/)" after merge.

### Deployment Pipeline

1. GitHub - Version Control System
   - <https://github.com/tmknom/continuous-writing>
2. CircleCI - Continuous Integration
   - <https://circleci.com/gh/tmknom/continuous-writing>
3. Docker Hub - Docker Registry
   - <https://hub.docker.com/r/tmknom/continuous-writing>
4. MicroBadger - Docker Inspection
   - <https://microbadger.com/images/tmknom/continuous-writing>

## License

Apache 2 Licensed. See LICENSE for full details.
