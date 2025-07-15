FROM node:18

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

RUN mkdir -p Uploads public

EXPOSE 3083

CMD ["node", "server.js"]

