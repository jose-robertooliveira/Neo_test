FROM alpine:3.16


COPY new_base.sql /docker-entrypoint-initdb.d/

ENV PG_USER=postgres

ENTRYPOINT ["/usr/local/bin/docker-entrypoint.sh"]
