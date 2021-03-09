FROM node:14

ARG PORT=1337
ENV DEFAULT_PORT $PORT

WORKDIR /usr/src

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE $DEFAULT_PORT
CMD ["npm", "run", "start"]