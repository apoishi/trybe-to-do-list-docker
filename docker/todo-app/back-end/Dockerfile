# FROM node:14-alpine AS build
# WORKDIR /todo-app/back-end/
# COPY package*.json ./
# RUN npm install
# COPY . .
# ADD node_modules.tar.gz ./
# EXPOSE 3001
# CMD ["npm", "start"]

FROM node:14-alpine
WORKDIR /usr/app
EXPOSE 3001
ADD ./node_modules.tar.gz ./
COPY . .
CMD [ "npm", "start" ]