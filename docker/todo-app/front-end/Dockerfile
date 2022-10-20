FROM node:14-alpine

WORKDIR /usr/local

EXPOSE 3000

# REACT_APP_API_HOST todobackend
# REACT_APP_API_PORT 3000

ADD node_modules.tar.gz /usr/local/bin/

COPY . .

RUN npm install

CMD [ "npm", "start" ]



