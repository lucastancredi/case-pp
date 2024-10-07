# case-pp

Aqui tentei baixar os arquivos de forma incremental, respeitando M-2 e um histórico de 3 meses anteriores.
Os mesmos são inseridos em uma tabela raw e em seguida colocados em uma tabela Silver para que sejam ajustados.
Utilizei o formato Delta por permitir ACID e time travel de forma facilitada, particionando por ano e mês.
