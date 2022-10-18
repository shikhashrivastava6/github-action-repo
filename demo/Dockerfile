# TODO: complete this file
FROM node:alpine3.15
WORKDIR /demo
COPY package*.json ./
RUN npm install
COPY . .
CMD [ "node", "./server.js" ]
EXPOSE 9000