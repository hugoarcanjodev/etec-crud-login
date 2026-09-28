# Etec - CRUD PHP com Login


```sql
CREATE TABLE `pwii`.`usuario` (
  `idusuario` INT NOT NULL AUTO_INCREMENT,
  `nome` VARCHAR(45) NOT NULL,
  `senha` VARCHAR(100) NOT NULL,
  PRIMARY KEY (`idusuario`)
);

INSERT INTO `pwii`.`usuario` (`nome`, `senha`) 
VALUES ('gabi', 'gabi123');
```