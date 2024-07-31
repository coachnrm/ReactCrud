FROM node:18-slim

WORKDIR /usr/src/app

COPY ./package.json ./

RUN yarn install

COPY . .

EXPOSE 5000

CMD ["Server.js"]