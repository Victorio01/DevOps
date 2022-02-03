FROM node:16.13.1-alpine

WORKDIR /app/src

COPY capstone_project/hello-world/package.json ./
COPY capstone_project/hello-world/package-lock.json ./

RUN npm install

COPY . .

CMD ["npm", "start"]
