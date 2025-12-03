FROM node:18.20.1-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install --production

COPY . .

EXPOSE 80

CMD ["node", "server.js"]