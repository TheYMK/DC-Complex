# DOCKERFILE TO BE USED DURING PROD ONLY
FROM node:16-alpine

WORKDIR /usr/src/app

COPY ./package.json ./
RUN npm install
COPY . .

CMD ["npm", "run", "start"]