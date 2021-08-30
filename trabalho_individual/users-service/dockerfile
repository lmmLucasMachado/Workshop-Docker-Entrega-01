FROM node:16.7-alpine3.14

WORKDIR /user-service

COPY . .

RUN yarn

CMD yarn db:migrate && yarn watch

EXPOSE 7101
