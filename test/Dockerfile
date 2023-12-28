FROM node:18-alpine3.15 

WORKDIR /src/app

COPY package.json ./

COPY package-lock.json .

RUN npm install

COPY ./ ./

EXPOSE 3000

CMD ["node", "index.js"]

