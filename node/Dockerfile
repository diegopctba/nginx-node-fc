FROM node:15

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install --save

COPY . .

RUN ls -la

EXPOSE 3000

CMD ["node", "index.js"]
