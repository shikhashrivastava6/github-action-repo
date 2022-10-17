# TODO: complete this file
FROM node:alpine3.16
WORKDIR /demo
COPY package*.json ./
RUN npm install
COPY . .
CMD [ "node", "./server.js" ]
EXPOSE 9000