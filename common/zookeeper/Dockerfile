# FROM frolvlad/alpine-oraclejdk8:slim
FROM zookeeper

MAINTAINER yzw


ENV TZ=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone