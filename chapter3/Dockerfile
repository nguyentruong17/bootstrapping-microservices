FROM node:17.3-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN yarn install --prod
COPY ./src ./src
COPY ./videos ./videos
CMD yarn start