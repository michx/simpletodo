FROM node:10-alpine

WORKDIR /usr/src/app

COPY backend/package*.json ./

COPY backend/server.js ./

RUN npm install

COPY backend/. .

EXPOSE 3001

CMD ["node", "server.js"]