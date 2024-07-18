FROM node:14.5.0-alpine

WORKDIR /bezkoder-app
COPY /bezkoder-app/package.json .
RUN npm install
COPY . .
CMD npm start
