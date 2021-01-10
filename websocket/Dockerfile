FROM node:lts

RUN npm install -g nodemon
RUN npm install websocket

COPY ./app /app
WORKDIR /app
 
CMD nodemon server.js
