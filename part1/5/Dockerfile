FROM node:11.6-alpine

WORKDIR /app
COPY package.json /app
RUN apk update && \ 
    apk add nodejs && \
    apk add bash && \
    apk add curl && \
    npm install
COPY . /app

CMD npm start

EXPOSE 5000