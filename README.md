# Docker Distribution

## Introduction

ArchCI provides docker distribution or registry to manage base images.

It's the official [registry](https://github.com/docker/registry) container!

## Usage

```
docker run -d -e /registry=/registry -p 5000:5000 registry
```

Or use docker distribution

```
docker run -d -p 5000:5000 registry:2.0
```