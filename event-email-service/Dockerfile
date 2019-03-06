FROM node:alpine

LABEL source=git@github.com:kyma-project/examples.git

WORKDIR /usr/src/app

COPY . .

RUN npm install

EXPOSE 8080

CMD [ "npm", "start" ]
