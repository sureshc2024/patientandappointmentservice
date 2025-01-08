FROM node:20-alpine

USER root

WORKDIR /usr/src/app 

COPY package*.json .

RUN npm install

COPY . . 

EXPOSE 3000

CMD [ "node","patient.js" ]