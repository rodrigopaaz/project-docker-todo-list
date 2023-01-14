FROM mjgargani/puppeteer:trybe1.0

WORKDIR /home/puser/node_modules/puppeteer

ADD ./node_modules.tar.gz .

CMD [ "npm", "test" ]

COPY . .