FROM node:alpine As development

WORKDIR /user/src/app2

COPY package*.json ./

RUN npm install

COPY . .

RUN npm run build