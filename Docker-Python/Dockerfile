FROM python:3

ENV APP_PATH=/app
RUN mkdir ${APP_PATH}
WORKDIR ${APP_PATH}

RUN apt-get update
RUN pip install --upgrade pip

# COPY requirements.txt ./
# RUN pip install -r requirements.txt

COPY . .
