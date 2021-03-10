FROM node:14

WORKDIR /usr/src

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE $PORT
CMD ["npm", "run", "start"]