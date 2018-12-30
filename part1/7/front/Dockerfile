FROM node:11.6-alpine

WORKDIR /app
COPY package.json /app
RUN npm install
COPY . /app

CMD API_URL=http://localhost:8000 npm start

EXPOSE 5000