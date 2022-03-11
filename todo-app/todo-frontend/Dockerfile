FROM node:16 AS build-stage

WORKDIR /usr/src/app

COPY . .

RUN npm ci

CMD [ "npm", "run", "build" ]