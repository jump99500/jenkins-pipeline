FROM node:16.13.1-alpine

WORKDIR /app

COPY package.json /app/

RUN npm install

COPY . /app

EXPOSE 3000

CMD ["node", "./src/index.js"]