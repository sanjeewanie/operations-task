FROM postgres:latest
ENV POSTGRES_PASSWORD=postgres
ENV POSTGRES_USER=postgres
ENV POSTGRES_DB=rates
COPY rates.sql /docker-entrypoint-initdb.d/rates.sql