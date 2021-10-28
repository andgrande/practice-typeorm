Praticando consultas no banco de dados com o TypeORM de três maneiras:

- Usando o ORM
- Usando Query Builder
- Usando Raw Query

A aplicação possui dois módulos: users e games. Um usuário pode ter vários jogos e um mesmo jogo pode estar associado a vários usuários.

Para criar o banco postgres:
```bash
docker run --name ignite-challenge-database-queries -e POSTGRES_DB=queries_challenge -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```