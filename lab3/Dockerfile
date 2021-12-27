FROM node:14.9

WORKDIR /usr/src/app

copy package*.json ./

RUN npm install

copy . .

EXPOSE 3000

CMD ["npm", "start"]
