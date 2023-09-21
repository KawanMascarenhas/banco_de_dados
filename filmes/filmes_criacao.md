# Comandos SQL - Referência
<!-- __________________________________________ -->
## Modelagem física

### Criar banco de dados

```sql

CREATE DATABASE filmes CHARACTER SET utf8mb4;

```
<!-- -->



```sql
CREATE TABLE filmes (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    titulo VARCHAR (45) NOT NULL,
    lançamento YEAR (4),
    genero_id INT NOT NULL
)
```


<!--  -->
 

 ```sql
CREATE TABLE generos (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    genero VARCHAR (45) NOT NULL
  
)
```



