

FROM node:lts-alpine
WORKDIR /client
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 9000
CMD ["node","index.js"]
