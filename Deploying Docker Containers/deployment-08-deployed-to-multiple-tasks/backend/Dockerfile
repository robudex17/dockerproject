FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=robudex17
ENV MONGODB_PASSWORD=R0bud3x@ES06171984
ENV MONGODB_URL=cluster0.eexlp.mongodb.net
ENV MONGODB_NAME=goals-dev

CMD ["npm", "start"]