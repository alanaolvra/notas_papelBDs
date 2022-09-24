## Anotações sobre Bancos de Dados SQL e NoSQL na Engenharia de Dados
* O que é um banco de dados relacional (SQL)?

É um banco em que se deseja armazenar informações que tenham relacionamento entre si. Um conjunto de dados normalizados, consistente, rígido. A SQL — Structured Query Language, ou linguagem estruturada de consultas — é a linguagem padrão dos chamados Bancos de Dados Relacionais que, por sua vez, são bancos de dados estruturados em forma de colunas e linhas, também chamadas de tuplas, tendo seus dados armazenados em tabelas.

1. DML: Data Manipulation Language

Comandos DML são comandos que tratam do conteúdo dos dados. Eles alteram as informações em um banco de dados SQL. Seus comandos mais usados, são:

SELECT - INSERT - DELETE - UPDATE

Esses comandos estão frequentemente inseridos no código dos programas que são usados para acessar e alterar as informações contidas no banco de dados. Eles também podem ser acionados por alguém que os execute diretamente no banco de dados, por meio de uma interface de conexão e gerenciamento do SGDB.

2. DDL: Data Definition Language

São comandos que criam ou alteram as estruturas das tabelas onde os dados estão armazenados. Seus comandos mais comuns são:

CREATE - ALTER - DROP

Esses comandos são acionados em situações de atualização de sistemas, em que novas estruturas — como tabelas, visões, procedimentos armazenados, entre outros — são criadas.

Geralmente, são executados pela figura do DBA (Database Administrator), que é o profissional responsável pela administração e manutenção de um sistema de banco de dados.

* O que é um banco de dados não relacional (NoSQL)?

NoSQL é a denominação de bancos de dados não tabulares, que armazenam dados em esquemas diferentes das tabelas relacionais, como documentos, grafos, pares chave-valor ou colunas.

Surgiu para lidar com big data, conjuntos de dados gigantescos e complexos surgidos com a web, após os anos 2000. 

Como bancos relacionais podem ser ineficientes para grandes quantidades de dados, principalmente dados não estruturados — que não podem ser dispostos em linhas e colunas, como o conteúdo de textos, áudios e vídeos —, NoSQL surgiu como solução.
