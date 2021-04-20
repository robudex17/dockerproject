FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV SERVERNAME="localhost"

CMD ["node", "app.js"]