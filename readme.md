# Exemplo de um DAO em uma tabela disponibilizado aos alunos da disiciplina de Desenvolvimento Web. 
Esse é um exemplo simples de um DAO no Spring Boot 3.3.5, utilizado para fins didáticos.

Exemplo de DAO simples considerando a seguinte tabela no mysql
CREATE TABLE produto (
  idproduto int auto_increment NOT NULL ,
  nome_do_produto varchar(45) DEFAULT NULL,
  quantidade_estoque int DEFAULT NULL,
  preco_produto double DEFAULT NULL,
  valor_estoque double DEFAULT NULL,
  PRIMARY KEY (idproduto)
);
------------------------------------------------------------------------------
Diretorios:
controller: Especifica as rotas e os metodos invocados pelas mesmas.
model: Contem as classes dos objetos das tabelas do banco.
service: Contem os codigos das consultas SQL ao banco de dados.
