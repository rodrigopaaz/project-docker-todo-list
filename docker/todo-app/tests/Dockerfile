FROM mjgargani/puppeteer:trybe1.0

COPY . ./app

ADD ./node_modules.tar.gz .

WORKDIR /app

CMD [ "npm", "test" ]