FROM node:18-alpine

ENV NODE_OPTIONS=--openssl-legacy-provider

RUN apk add --no-cache git

WORKDIR kriketOS
COPY . .

RUN yarn
RUN yarn build

CMD yarn serve
