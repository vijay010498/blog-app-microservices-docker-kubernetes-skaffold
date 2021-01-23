FROM node:alpine

#working directory

WORKDIR /usr/src/app

COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]