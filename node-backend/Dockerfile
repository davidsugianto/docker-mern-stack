FROM node:13.2-alpine

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

RUN npm install
RUN npm install -g nodemon

EXPOSE 3000
CMD [ "npm", "start" ]
