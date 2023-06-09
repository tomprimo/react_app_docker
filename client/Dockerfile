FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app
COPY ./client/package*.json ./
RUN npm i
COPY ./client/src src
COPY ./client/public public

CMD npm start