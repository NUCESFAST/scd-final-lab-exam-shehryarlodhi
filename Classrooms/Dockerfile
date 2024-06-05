# Classrooms/Dockerfile
FROM node:14-alpine

WORKDIR /1772_classrooms_backend

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3772

CMD ["npm", "start"]
