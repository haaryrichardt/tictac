FROM node:10

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install --silent

COPY . .

RUN npm run --silent build

EXPOSE 8080

CMD [ "node", "server.js" ]
