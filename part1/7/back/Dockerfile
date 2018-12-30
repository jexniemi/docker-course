FROM node:11.6-alpine

WORKDIR /app
COPY package.json /app
RUN npm install
COPY . /app

CMD FRONT_URL=http://localhost:5000 npm start

EXPOSE 8000