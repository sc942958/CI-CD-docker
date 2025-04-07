FROM node:20

RUN mkdir /node && apk update && apk add git
ADD server.js /node
WORKDIR /node

EXPOSE 8080
WORKDIR /node
CMD ["node", "server.js"]
