FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

ADD ./node_modules.tar.gz .

COPY . ./app/files

CMD [ "npm", "test" ]