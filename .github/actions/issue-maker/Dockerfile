FROM node:slim

COPY package*.json ./

#RUN npm cache clean --force

#RUN npm install

RUN npm rebuild

COPY . .

CMD [ "node", "/src/index.js" ]
