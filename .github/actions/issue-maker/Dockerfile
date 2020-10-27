FROM node:slim

COPY package*.json ./

RUN npm cache clean --force

RUN npm install

COPY . .

CMD [ "node", "/src/index.js" ]
