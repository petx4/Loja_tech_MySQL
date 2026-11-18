🛒 Loja Tech — Banco de Dados MySQL

Projeto de banco de dados desenvolvido em MySQL para simular o gerenciamento de uma loja de produtos tecnológicos. O sistema organiza informações de clientes, produtos, categorias, pedidos e operações, permitindo estruturar e gerenciar os dados de uma loja de tecnologia.

🎯 Objetivo do Projeto

O objetivo deste projeto é desenvolver e organizar um banco de dados relacional para uma loja de tecnologia, aplicando conceitos de SQL e MySQL, como criação de tabelas, definição de chaves primárias, restrições de unicidade e armazenamento de dados.

🗄️ Tecnologias Utilizadas
MySQL 8.0 — Sistema de gerenciamento de banco de dados.
SQL — Linguagem utilizada para criação e manipulação dos dados.
InnoDB — Engine de armazenamento das tabelas.
📁 Estrutura do Projeto

O projeto está organizado nos seguintes arquivos:

Arquivo	Descrição
loja_tech_categorias.sql	Armazena as categorias dos produtos.
loja_tech_clientes.sql	Armazena os dados dos clientes.
loja_tech_produtos.sql	Contém os produtos disponíveis na loja.
loja_tech_pedidos.sql	Armazena os pedidos realizados.
loja_tech_itens_pedido.sql	Registra os produtos associados aos pedidos.
loja_tech_log_operacoes.sql	Armazena registros de operações.
📋 Funcionalidades e Organização

O banco de dados contempla:

Clientes: cadastro de nome, e-mail, CPF, telefone e data de nascimento.
Categorias: organização dos produtos por tipo, como notebooks, smartphones, periféricos, monitores, armazenamento e acessórios.
Produtos: armazenamento das informações dos produtos da loja.
Pedidos: organização dos pedidos realizados pelos clientes.
Itens de pedido: associação dos produtos aos respectivos pedidos.
Log de operações: registro de operações realizadas no banco de dados.
⚙️ Como Executar o Projeto
1. Pré-requisitos

Antes de começar, é necessário ter instalado:

MySQL Server 8.0 ou superior.
MySQL Workbench ou outro cliente SQL de sua preferência.
Git (opcional, para clonar o repositório).
2. Clonar o repositório

Abra o terminal e execute:

bash
git clone https://github.com/petx4/Loja_tech_MySQL.git


Entre na pasta do projeto:

bash
cd Loja_tech_MySQL

3. Criar o banco de dados

No MySQL Workbench, execute:

sql
CREATE DATABASE loja_tech;

USE loja_tech;

4. Importar os arquivos SQL

Execute os arquivos .sql disponibilizados no projeto pelo MySQL Workbench, utilizando a opção de abertura de arquivos SQL.

Certifique-se de selecionar o banco de dados loja_tech antes da execução.

5. Verificar as tabelas

Após a importação, execute:

sql
USE loja_tech;

SHOW TABLES;


Isso permitirá visualizar as tabelas disponíveis no banco de dados.

🧪 Exemplos de Consultas SQL

Consultar os clientes cadastrados:

sql
SELECT * FROM clientes;


Consultar as categorias:

sql
SELECT * FROM categorias;


Consultar os produtos:

sql
SELECT * FROM produtos;


Consultar os pedidos:

sql
SELECT * FROM pedidos;

📚 Aprendizados

Este projeto permite praticar conceitos importantes de banco de dados relacionais, incluindo:

Criação e estruturação de bancos de dados.
Criação e manipulação de tabelas.
Utilização de chaves primárias.
Aplicação de restrições de unicidade.
Inserção e consulta de registros.
Organização de informações em um banco de dados relacional.
Utilização da linguagem SQL.
👩‍💻 Autoria

Projeto desenvolvido por petx4, com foco em aprendizado e prática de banco de dados utilizando MySQL.

📄 Licença

Este projeto foi desenvolvido para fins educacionais e de estudo.
