FROM mcr.microsoft.com/devcontainers/base:alpine-3.18

RUN set -x \
  && apk update \
  && apk upgrade \
  && apk add --update nodejs npm \
  && apk add python3 \
  && apk add py3-pip \
  && apk add redis \
  && pip install -U fastapi \
  && pip install -U uvicorn \
  && pip install black \
  && npm install -g typescript \
  && pip install yfinance \
  && pip install pipreqs \
  && pip install pytest \
  && pip install python-dotenv \
  && pip install pydantic \
  && pip install pytest-asyncio \
  && pip install sqlalchemy \
  && pip install openapi-python-client \
  && pip install PyJWT \
  && pip install pyjwt[crypto] \
  && pip install isort \
  && pip install redis \
  && pip install apscheduler
