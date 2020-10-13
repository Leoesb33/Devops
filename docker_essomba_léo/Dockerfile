FROM alpine:latest

RUN apk update && \
  apk add npm

WORKDIR /tpDocker

COPY tp-1-docker /tpDocker

RUN npm install

CMD npm start