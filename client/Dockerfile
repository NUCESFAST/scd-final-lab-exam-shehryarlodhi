# client/Dockerfile
FROM node:14-alpine

WORKDIR /1771_frontend

COPY package*.json ./

RUN npm install

COPY . .

RUN npm run build

EXPOSE 1771

CMD ["npm", "start"]
