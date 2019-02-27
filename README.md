# docker-cloc [![Docker Automated build](https://img.shields.io/docker/automated/agua3/cloc.svg)](https://hub.docker.com/r/agua3/cloc)

Small docker image for [`cloc`](https://github.com/AlDanial/cloc), based on Linux Alpine. It includes `git`, so it can be called with `--vcs=git`.

## Usage

```
docker run --rm --volume /path/to/your/code:/code agua3/cloc --vcs=git .
```
