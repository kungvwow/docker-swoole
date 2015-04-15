docker-swoole
=============

A docker-swoole image base on centos:6, help you easy play with [swoole](https://github.com/swoole), enjoy.

*Install Docker*
[Visit Docker-Doc](https://docs.docker.com/)


**Start Docker**
```shell
service docker start
chkconfig docker on
```

**Get docker-swoole**
```shell
docker pull betashepherd/docker-swoole
```

**Run docker-swoole image**
```shell
docker run -i -t betashepherd/docker-swoole:1.7.15-stable /bin/bash
bash-4.1# php -r "echo SWOOLE_VERSION;"
```
