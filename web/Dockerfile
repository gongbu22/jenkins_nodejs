FROM node:18.20.4-alpine3.20
WORKDIR /app
COPY package.json /app
RUN npm install
COPY ./public /app/public
COPY ./src /app/src
EXPOSE 3000
CMD ["node", "src/server.js"]