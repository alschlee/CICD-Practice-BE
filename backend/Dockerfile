FROM node:20

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm install

COPY . .
COPY .env ./

EXPOSE 8888
CMD ["npm", "run", "dev"]