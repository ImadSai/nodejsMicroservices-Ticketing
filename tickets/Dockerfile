# --------
FROM node:alpine

WORKDIR /app

COPY package.json .

RUN npm install -g npm@7.20.6

RUN npm install --production --legacy-peer-deps

COPY . .

CMD [ "npm", "start" ]
