FROM node:current-alpine
WORKDIR /app
COPY package*.jason /

RUN yarn install

COPY . ./
CMD ["yarn", "start"]