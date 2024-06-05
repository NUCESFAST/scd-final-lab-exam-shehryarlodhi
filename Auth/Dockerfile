# Auth/Dockerfile
FROM node:14-alpine

WORKDIR /1771_auth_backend

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3771

CMD ["npm", "start"]
