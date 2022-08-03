FROM node:14-alpine AS todofrontend

WORKDIR /front

COPY package*.json .

COPY . .

EXPOSE 3000

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
