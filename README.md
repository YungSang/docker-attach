# docker-attach

Helper scripts to attach to a container with Docker and libcontainer

Cf.) [Attaching to a container with Docker 0.9 and libcontainer](http://jpetazzo.github.io/2014/03/23/lxc-attach-nsinit-nsenter-docker-0-9/)

## Using nsenter

```
$ docker-nsenter
Usage: docker-nsenter <container id/name> [{command:-$SHELL} [argments...]]
```

## Using nsinit
```
$ docker-nsinit
Usage: docker-nsinit <container id/name> [{command:-$SHELL} [argments...]]
```
