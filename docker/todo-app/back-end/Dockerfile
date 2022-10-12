FROM node:14-alpine

EXPOSE 3001

WORKDIR /src

COPY /src ./src 

ADD node_modules.tar.gz ./todobackend 

ENTRYPOINT [ "npm", "start" ]