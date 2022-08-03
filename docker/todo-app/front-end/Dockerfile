FROM node:14-alpine AS todofrontend

WORKDIR /app

COPY package*.json /app/

RUN npm install

ADD node_modules.tar.gz /app/

COPY . /app/

ENV REACT_APP_API_HOST=localhost

ENV REACT_APP_API_PORT=3001

EXPOSE 3000

ENTRYPOINT [ "npm" ]

CMD [ "test" ]
