FROM node:14-alpine

WORKDIR  /usr/path

COPY ./package.json ./

RUN npm install

COPY ./ ./

CMD ["npm", "start"]