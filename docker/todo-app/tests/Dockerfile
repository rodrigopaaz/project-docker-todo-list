FROM mjgargani/puppeteer:trybe1.0

COPY . /usr/local/bin/

ADD ./node_modules.tar.gz /usr/local/bin/

WORKDIR /app

CMD [ "npm", "test" ]
