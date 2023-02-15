FROM node:lts-alpine3.17
RUN npm install -g nodemon

WORKDIR /app
COPY package.json .
RUN npm install

COPY . .
EXPOSE 8080

CMD ["npm","start"]