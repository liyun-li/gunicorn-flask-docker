FROM python:3.6-alpine

RUN apk add --no-cache build-base
COPY req.txt /tmp/
RUN pip install -r /tmp/req.txt
