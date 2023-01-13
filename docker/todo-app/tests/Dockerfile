FROM mjgargani/puppeteer:trybe1.0

COPY . .

ADD ./node_modules.tar.gz .

WORKDIR /app

CMD [ "npm", "test" ]