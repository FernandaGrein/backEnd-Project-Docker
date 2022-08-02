FROM node:14-alpine AS todobackend

WORKDIR /app

COPY package*.json /app/

RUN npm install

ADD node_modules.tar.gz /app/

COPY . /app/

EXPOSE 3001

ENTRYPOINT [ "npm" ]

CMD [ "start" ]