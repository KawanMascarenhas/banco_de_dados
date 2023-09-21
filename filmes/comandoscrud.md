# Comandos SQL - Para CRUD (Referência)

## Resumo
C -> Create (Insere dados)
R -> Read (Ler dados)
U -> Update (Atualizar dados)
D -> Delete (Deletar dados)

<!-- ______________________________________________ -->

## Insert
## Generos

```sql
INSERT INTO generos (genero) VALUES('Ação');
INSERT INTO generos (genero) VALUES('Aventura');
INSERT INTO generos (genero)
VALUES('Romance'),('Comédia'),('Terror'),('Suspense');

```
<!-- ________________________________________________ -->

```sql
INSERT INTO filmes (titulo, lancamento,genero_id) VALUES(
'O Poderoso Chefão',
'2000',
1
);
INSERT INTO filmes (titulo, lancamento,genero_id) VALUES(
'IT a coisa',
'2020',
5
);
INSERT INTO filmes (titulo, lancamento,genero_id) VALUES(
'TED',
'2016',
4
);


```