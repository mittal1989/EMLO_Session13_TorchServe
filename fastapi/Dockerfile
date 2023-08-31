FROM python:3.9-slim

WORKDIR /workdir

COPY ./requirements.txt /workdir/requirements.txt

RUN pip install --no-cache-dir --upgrade -r /workdir/requirements.txt

EXPOSE 8080

COPY ./server.py /workdir/