FROM node:14-alpine

WORKDIR /usr/src/app

COPY package*.json .

RUN npm install

RUN npm install -g @vue/cli

EXPOSE 8080

CMD ["npm", "run", "serve"]

# see vuejs doc for prod build dockerization