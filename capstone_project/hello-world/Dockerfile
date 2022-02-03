FROM node:16.13.1-alpine

WORKDIR /app/src

COPY ./package.json ./
COPY ./package-lock.json ./

RUN npm install

COPY . .

CMD ["npm", "start"]
