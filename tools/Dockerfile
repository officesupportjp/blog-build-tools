FROM node:16-slim
ENV SHELL /bin/bash


WORKDIR /root

# set -ex コマンドの実行に失敗したらその場で終了する
RUN set -ex\
    && apt-get update\
    && apt-get -y install git\
    && git config --global user.name "${GIT_USERNAME}"\
    && git config --global user.email "${GIT_EMAIL}"

# set -ex コマンドの実行に失敗したらその場で終了する
RUN set -ex\
    && git clone "${GIT_REPO}"\
    && cd blog\
    && npm install
