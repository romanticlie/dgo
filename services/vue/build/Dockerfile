FROM node:15-alpine

LABEL author=charlie

RUN npm config set registry http://registry.npm.taobao.org && \
    yarn global add @vue/cli && \
    npm install -g @vue/cli-service-global

WORKDIR /www

