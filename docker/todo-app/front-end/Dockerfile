FROM node:14-alpine AS todofrontend

WORKDIR /app

COPY package*.json /app/

RUN npm install

ADD node_modules.tar.gz /app/

COPY . /app/

EXPOSE 3000

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
