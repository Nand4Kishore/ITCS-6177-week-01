FROM node:15

WORKDIR /app

COPY package*.json ./

RUN npm install express

COPY . .

ENV PORT=8080

EXPOSE 8080

CMD [ "npm", "start" ]