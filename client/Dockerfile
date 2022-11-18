FROM node:18

WORKDIR /src/frontend

COPY *.json ./

RUN yarn global add @quasar/cli

RUN yarn install

CMD ['quasar dev', 'quasar test --unit jest']

COPY . .

EXPOSE 3000