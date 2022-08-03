FROM mjgargani/puppeteer:trybe1.0 AS todotests

WORKDIR /app

COPY package*.json /app/

RUN npm install

ADD node_modules.tar.gz /app/

COPY . /app/

ENTRYPOINT [ "npm" ]

CMD [ "test" ]

