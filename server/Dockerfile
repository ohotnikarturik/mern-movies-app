FROM node:12-alpine

WORKDIR  /usr/src/app

COPY package.json yarn.lock ./

RUN yarn install

COPY . .

EXPOSE 5000

CMD ["index.js"]