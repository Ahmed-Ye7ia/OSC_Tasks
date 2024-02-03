FROM ubuntu:20.04

RUN npm install

COPY package*.json /app/
COPY src /app/

WORKDIR /app

CMD ["node", "app.js"]
