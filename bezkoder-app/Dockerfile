FROM node:14.5.0-alpine

WORKDIR /bezkoder-app
COPY package.json .
RUN npm install
COPY . .
CMD npm start
