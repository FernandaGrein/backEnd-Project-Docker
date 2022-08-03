FROM node:14-alpine AS todofrontend

WORKDIR /front

COPY package*.json /front/

RUN npm install

ADD node_modules.tar.gz /front/

COPY . /front/

EXPOSE 3000

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
