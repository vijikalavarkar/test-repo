FROM node:18.9.1

WORKDIR /app

COPY package*.json /app/

RUN npm i --force

RUN npm i nodemon

EXPOSE 4000

CMD [ "npm","run","dev" ]