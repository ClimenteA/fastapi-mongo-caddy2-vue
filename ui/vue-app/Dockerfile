FROM node:14

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

COPY package*.json ./


RUN npm install -g @vue/cli-service && npm install


COPY . .


CMD npm run serve