FROM python:3.7.4

ARG POETRY_VERSION=0.12.17
ARG PIPENV_VERSION=2018.11.26

RUN apt-get update && apt-get install sudo curl git -y

# Install & setup Poetry
RUN pip install --no-cache "poetry==${POETRY_VERSION}" "pipenv==${PIPENV_VERSION}"
# RUN poetry config settings.virtualenvs.create false

ENV PATH="/root/.local/bin:$PATH"

WORKDIR /code
