FROM postgres:14.1-alpine

COPY sql docker-entrypoint-initdb.d

ENV POSTGRES_DB=db \
   POSTGRES_USER=usr \
   POSTGRES_PASSWORD=pwd
