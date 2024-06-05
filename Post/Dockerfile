# post/Dockerfile
FROM node:14-alpine

WORKDIR /1774_posts_backend

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3774

CMD ["npm", "start"]
