FROM node:18

USER root

WORKDIR /app 

COPY package*.json ./

RUN npm install

COPY . . 

EXPOSE 3000

CMD [ "node","patient.js" ]