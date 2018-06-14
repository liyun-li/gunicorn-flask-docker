FROM fdsa/gunicorn-flask:base

RUN apk add --no-cache mysql-dev
COPY r.txt /tmp/
RUN pip install mysql-connector
