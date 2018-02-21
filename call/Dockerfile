FROM node:alpine

COPY ./ /server

WORKDIR /server

RUN npm install

CMD ["node", "server.js"]