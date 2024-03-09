FROM node:alpine AS builder

WORKDIR /app

COPY . .

RUN npm i

EXPOSE 5000

CMD [ "node", "server.js" ]