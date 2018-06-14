FROM fdsa/gunicorn-flask:base

RUN apk add --no-cache postgresql-dev
COPY r.txt /tmp/
RUN pip install -r /tmp/r.txt
