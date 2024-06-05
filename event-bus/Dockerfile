# event-bus/Dockerfile
FROM node:14-alpine

WORKDIR /1773_event_bus_backend

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3773

CMD ["npm", "start"]
