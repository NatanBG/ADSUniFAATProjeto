
FROM postgres:latest


ENV POSTGRES_USER=admin
ENV POSTGRES_PASSWORD=senha
ENV POSTGRES_DB=Escola


COPY init.sql /docker-entrypoint-initdb.d/

EXPOSE 5432

