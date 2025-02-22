FROM node:18.9.1

WORKDIR /app

COPY package*.json /app/

RUN npm i --force

COPY . .

EXPOSE 5173

CMD [ "npm","run","dev" ]