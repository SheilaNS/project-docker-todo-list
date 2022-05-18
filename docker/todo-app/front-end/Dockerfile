FROM node:14-alpine AS build
WORKDIR /todo-app/front-end/
COPY package*.json ./
RUN npm install
COPY . .
ADD node_modules.tar.gz ./
EXPOSE 3000
CMD ["npm", "start"]
