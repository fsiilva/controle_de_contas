# controle_de_contas
Sistema, desenvolvido com as tecnologias Java e Mysql para cadastro e controle de pagamentos.
Projeto foi desenvolido para uma atividade de extenção da diciplina de progrmação orientada a objeto, da faculdade de analise e desenvolcido de sistema 2024.1
Foi utilizado banco de dado MySql e Linguagem Java.
# Banco de dados 
  Para implementação do banco de dados
  criar um banco de dadod chamado controle_decontas com uma tabela documentos
  CREATE TABLE IF NOT EXISTS documentos (     id INT AUTO_INCREMENT PRIMARY KEY,     data DATE NOT NULL,     numero_documento VARCHAR(50) NOT NULL,     valor_documento DECIMAL(10, 2) NOT NULL,     tipo_documento          VARCHAR(50) NOT NULL,     observacao TEXT );
