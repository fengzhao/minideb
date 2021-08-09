# minideb简介

minideb是一个最小的基于debian的镜像，专用于做基镜像。

# 使用

可以直接使用，例如：
```shell
$ docker run --rm -it bitnami/minideb:latest
```
可以用不同的tag来使用不同的发行版
```shell
$ docker run --rm -it bitnami/minideb:stretch
```
这个基镜像每天更新，包括安全更新。所以它会包括超过24小时的发布的安全更新。

可以在 Dockerfile 中使用这个基镜像：
```Dockerfile
FROM bitnami/minideb:stretch
```
# 为什么要用minideb

