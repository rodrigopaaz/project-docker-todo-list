FROM node:14

COPY . /usr/local/bin/

ADD ./node_modules.tar.gz /usr/local/bin/

WORKDIR /app

CMD [ "npm", "start" ]

EXPOSE 3000