FROM node:14.18-alpine

ENV PROJECT_ROOTDIR /usr/src/app

WORKDIR $PROJECT_ROOTDIR

COPY package.json package-lock.json $PROJECT_ROOTDIR

RUN yarn install

COPY . $PROJECT_ROOTDIR

EXPOSE 3000

CMD ["yarn", "start"]
