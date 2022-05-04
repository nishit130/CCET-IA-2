
FROM node:12-slim as todo-client

WORKDIR /client/


COPY package*.json ./
RUN npm install
COPY . .

CMD [ "npm", "start" ]

EXPOSE 3000