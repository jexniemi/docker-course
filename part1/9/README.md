Alpine linux with node 11.6 installed, includes some additional tools such as bash, http-server and create-react-app for React development

Dockerfile:

FROM node:11.6-alpine

RUN apk update && \
    apk add bash && \
    npm install -g create-react-app && \
    npm install -g http-server


https://cloud.docker.com/repository/registry-1.docker.io/jexniemi/node-react-sample

Run and access container:

docker run --rm -d -it --name node-react-base node-react-base

docker exec --it node-react-base bash