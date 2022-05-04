FROM node:12-slim as todo-server

WORKDIR /server/

COPY package*.json ./

RUN npm install

COPY . .
