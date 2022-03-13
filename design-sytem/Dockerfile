FROM node:16

WORKDIR /usr/app

COPY ./package.json .

RUN yarn add global expo-cli

RUN yarn install

COPY . .


ARG PORT=19006
ENV PORT $PORT
EXPOSE $PORT 19000 19002 19001


CMD ["yarn","start"]





