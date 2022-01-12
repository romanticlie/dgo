FROM node:16.13.1-alpine3.14

LABEL author=charlie

RUN npm config set registry http://registry.npm.taobao.org && \
    yarn global add @vue/cli && \
    npm install -g @vue/cli-service-global

WORKDIR /www

