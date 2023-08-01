FROM node:13-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
RUN npm install react-scripts --save
COPY . .
EXPOSE 3000
RUN npm run build
