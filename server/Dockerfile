FROM node:lts-alpine3.17

WORKDIR /app/client
COPY package.json .
RUN npm install

COPY . .
EXPOSE 8000

CMD ["npm","start"]