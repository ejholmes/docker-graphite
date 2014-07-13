# Docker Graphite

A docker container for running [graphite web](https://github.com/graphite-project/graphite-web).

## Usage

This is meant to be run on the same machine as [docker-carbon](https://github.com/ejholmes/docker-carbon), so make sure you start that first.

```bash
$ docker run --rm --name graphite -p 8080:80 --volumes-from carbon ejholmes/graphite
```
