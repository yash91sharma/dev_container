FROM mcr.microsoft.com/devcontainers/base:alpine-3.18

RUN set -x \
  && apk update \
  && apk upgrade \
  && apk add --update nodejs npm \
  && apk add python3 \
  && apk add py3-pip \
  && pip install -U Flask \
  && pip install black \
  && pip install waitress \
  && npm install -g typescript \
  && pip install yfinance \
  && pip install pipreqs \
  && pip install flask-cors \
  && pip install gunicorn \
  && pip install pytest \
  && pip install python-dotenv
