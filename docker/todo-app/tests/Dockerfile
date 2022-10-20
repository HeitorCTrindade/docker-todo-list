FROM mjgargani/puppeteer:trybe1.0

WORKDIR /usr/local

ADD node_modules.tar.gz /bin

COPY . .

RUN npm install

CMD ("npm", "test")
