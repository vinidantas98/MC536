Estrutura de pastas:

~~~
├── README.md  <- arquivo apresentando a tarefa
~~~

# Aluno
* `188092`: `Vinicius Alves Mancine Dantas`

## Tarefa de Cypher sobre Marcadores e Taxonomia

## Tarefa 1

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, sem considerar as categorias subordinadas.

### Resolução
~~~cypher
MATCH (m:Marcador)-[:Pertence]->(c:Categoria)
WHERE c.id = 'Serviços'
return m
~~~

## Tarefa 2

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, considerando as categorias subordinadas.

### Resolução
~~~cypher
MATCH (m:Marcador)-[:Pertence]->()-[:Superior*0..2]->(c:Categoria)
WHERE c.id = 'Serviços'
RETURN m
~~~