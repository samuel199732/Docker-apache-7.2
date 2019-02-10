FROM node:10

LABEL maintainer="Samuel Silva <samuelsilva199732@gmail.com>"

RUN echo "---> Atualizando pacotes e instalando angular" && \
    apt-get update -y && \
    npm install -g @angular/cli@7 && \
    mkdir /usr/src/app

WORKDIR /usr/src/app

ENV PATH /usr/src/app/node_modules/.bin:$PATH

USER node