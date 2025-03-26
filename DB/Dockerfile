# Use a imagem oficial do Postgres
FROM postgres:latest

# Defina as variáveis de ambiente para o banco de dados
ENV POSTGRES_USER=admin
ENV POSTGRES_PASSWORD=senha
ENV POSTGRES_DB=Escola

# Copie o script SQL para criar o banco de dados e tabelas
COPY init.sql /docker-entrypoint-initdb.d/

# Expose a porta padrão do Postgres
EXPOSE 5432

