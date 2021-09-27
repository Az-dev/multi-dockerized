FROM node:16-alpine3.14

WORKDIR '/app'

COPY package.json .

RUN npm install

COPY . .

#the following will run the dev defined in script part in package.json which is "nodemon"
CMD ["npm","run","start"]