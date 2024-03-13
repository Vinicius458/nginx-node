FROM node:alpine AS builder

WORKDIR /usr/src/app

COPY . .

RUN npm i

EXPOSE 5000

CMD [ "node", "server.js" ]