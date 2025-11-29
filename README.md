# Projeto Orfanato Raio de Luz
Trabalho apresentado às disciplinas de Banco de Dados II e Linguagem de Programação II como requisito para a obtenção de nota da 3° unidade do 3° ano do ensino médio técnico no Instituto Federal da Bahia. Orientadores: Fabio Marques e Fernanda Regebe.
Sistema em **Java (NetBeans)** com **MySQL** para gerenciar um orfanato: crianças, adoções, funcionários, voluntários, finanças, saúde, educação e estoque.

## Pré-requisitos

- Java JDK 8 ou superior  
- NetBeans IDE  
- MySQL 8 ou superior  
- MySQL Connector/J (`mysql-connector-java-8.0.33.jar`) incluído na pasta `lib/`

## Configuração rápida

1. Certifique-se de que o banco `OrfanatoRLuz` já está criado e contém todas as tabelas.  
2. Abra o arquivo `DBConnection.java` e configure:

```java
private static final String URL = "jdbc:mysql://localhost:3306/OrfanatoRLuz";
private static final String USER = "USUÁRIO SQL";     // seu usuário MySQL
private static final String PASS = "SENHA SQL";    // sua senha MySQL

