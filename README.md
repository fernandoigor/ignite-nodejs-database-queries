

# Ignite - Rocketseat
###Desafio 01 - Database Queries

#### Sobre o desafio

Nesse desafio, você realizará consultas no banco de dados com o TypeORM de três maneiras:

- Usando o ORM
- Usando Query Builder
- Usando Raw Query

No template, existe uma aplicação já estruturada (apenas as entidades e repositórios) para completar o que falta nas consultas dos dois repositórios.

A aplicação possui dois módulos: `users` e `games`. Um **usuário** pode ter vários jogos e um mesmo **jogo** pode estar associado a vários usuários.


#### Preparando o ambiente para os testes
 - **Postgres** com o nome **queries_challenge**
 -  **Docker**	
 	- Create
``
docker run --name ignite-challenge-database-queries -e POSTGRES_DB=queries_challenge -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
``
 	- Stop
``
docker stop ignite-challenge-database-queries
``
 	- Start
``
docker start ignite-challenge-database-queries
``

#### Teste
 - **Yarn**
 	- Install
``
yarn
``
 	- Teste Jest
``
yarn test
``
 - **NPM**
 	- Install
``
npm install
``
 	- Teste Jest
``
npm run test
``