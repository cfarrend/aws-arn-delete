FROM python:3.7.4-alpine

ARG POETRY_VERSION=0.12.17

RUN apk add curl

# Install & setup Poetry
RUN pip install "poetry==${POETRY_VERSION}"
RUN poetry config settings.virtualenvs.create false

RUN apk add git

WORKDIR /code
