# clone-tabnews

Projeto de estudo implementando um clone do https://www.tabnews.com.br para o https://curso.dev

Link para a página: https://devchaves.com.br

# Banco de Dados

PostgreSQL - https://neon.tech

# Docker

Rodar o docker em background:

```
docker compose -f infra/compose.yaml up -d
```

Força a recriar o container:

```
docker compose up -f infra/compose.yaml -d --force-recreate
```

Executar o PSQL-Client:

```
psql --host=localhost --username=postgres --port=5432
```

Para listar o container em execução ou parado:

```
docker ps -a
```

Para parar/remover o container em execução:

```
docker compose -f infra/compose.yaml down
```
