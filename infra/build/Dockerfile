FROM node:18.14.2-alpine

WORKDIR /app

COPY ./package.json /package.json
COPY ./yarn.lock /yarn.lock

RUN yarn

COPY ./ /

EXPOSE 3000

CMD ["yarn", "start"]
