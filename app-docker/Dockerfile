ARG CODE_VERSION=16-alpine

FROM node:${CODE_VERSION}

WORKDIR /app

COPY package.json /app/

RUN npm install

COPY . /app 

CMD ["npm","start"]