FROM mjgargani/puppeteer:trybe1.0 AS todotests

WORKDIR /test

COPY package*.json /test/

RUN npm install

ADD node_modules.tar.gz /test/

COPY . /test/

ENTRYPOINT [ "npm" ]

CMD [ "test" ]

