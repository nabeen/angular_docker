FROM node:alpine

RUN apk --no-cache --update add \
git \
curl

RUN npm i -g \
@angular/cli

WORKDIR /app

ENV HOST 0.0.0.0

EXPOSE 80

EXPOSE 4200
