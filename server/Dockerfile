FROM node:8.10-alpine

RUN mkdir /app
WORKDIR /app

ADD ./package.json /app/package.json
ADD ./yarn.lock /app/yarn.lock
RUN yarn install

ADD . /app
