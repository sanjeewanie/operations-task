FROM postgres:latest

ENV POSTGRES_PASSWORD=postgres
ENV POSTGRES_USER=postgres
ENV POSTGRES_DB=rates
ENV POSTGRES_PORT=5432
ENV POSTGRES_HOST=db

COPY rates.sql /docker-entrypoint-initdb.d/rates.sql

