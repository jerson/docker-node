FROM node:14.17.0-alpine

ENV PYTHONUNBUFFERED=1
RUN apk add --update --no-cache alpine-sdk python3 && ln -sf python3 /usr/bin/python
RUN python3 -m ensurepip
RUN pip3 install --no-cache --upgrade pip setuptools
