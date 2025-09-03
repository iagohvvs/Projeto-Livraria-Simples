## 📖 Projeto-Livraria-Simples
Este projeto é um modelo de banco de dados simples para uma livraria, desenvolvido em SQL. Ele gerencia informações sobre livros e seus autores, permitindo a inserção, atualização e consulta de dados de forma eficiente. O objetivo é demonstrar os conceitos básicos de modelagem de dados e a execução de comandos SQL fundamentais.
## 📦 Pré-requisitos
  - MySQL, PostgreSQL, SQL Server ou Oracle
## 🚀 Exemplo de comandos para uso
  - Consultar todos os livros: SELECT * FROM Livros;
  - Consultar livros com preço acima de R$ 50: SELECT Titulo, preco FROM Livros WHERE preco > 50.00;
  - Consultar autores nascidos antes de 1980: SELECT nome, data_nascimento FROM Autores WHERE data_nascimento < '1980-01-01';
  - Atualizar o preço de um livro: UPDATE Livros SET preco = 79.90 WHERE Titulo = 'Crepúsculo';
## 📜 Licença
Este projeto está licenciado sob a licença MIT.

![SQL](https://img.shields.io/badge/Linguagem-SQL-blue)
![Status](https://img.shields.io/badge/status-completo-brightgreen)
