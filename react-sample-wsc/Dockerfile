FROM node:10.15-alpine
ENV APP_ROOT=/usr/src/app PJ_FROM=react-sample
WORKDIR $APP_ROOT
COPY $PJ_FROM/package.json $APP_ROOT
RUN npm i -g yarn && yarn install
COPY . $APP_ROOT
CMD ["yarn", "start"]
