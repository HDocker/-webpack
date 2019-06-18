FROM node:10
MAINTAINER Justin Firth <jmfirth@gmail.com>

RUN npm config set registry http://registry.npm.taobao.org
RUN npm install -g webpack webpack-dev-server yarn
RUN cp -r /usr/local/lib/node_modules /node_modules.bak


VOLUME /app

EXPOSE 3000

WORKDIR /app
