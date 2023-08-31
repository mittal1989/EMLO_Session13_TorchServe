From node:16-alpine

WORKDIR /usr/src/app

COPY package.json ./

RUN npm install 
RUN apk add --update curl

COPY . .

EXPOSE 3000

CMD [ "npm", "run", "dev" ]
