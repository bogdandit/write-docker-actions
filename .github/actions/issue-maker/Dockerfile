FROM node:lts-alpine3.9

COPY package*.json ./

RUN npm install

COPY . .

CMD [ "node", "/src/index.js" ]
