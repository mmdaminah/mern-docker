FROM node:18.15-alpine

WORKDIR /app/backend

COPY package.json .

RUN npm i

COPY . .

CMD npm start
