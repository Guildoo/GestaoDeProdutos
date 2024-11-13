# Sistema de Gestão de Estoque de Produtos

Este projeto implementa um **sistema de gestão de estoque de produtos** em Java, com o objetivo de fornecer uma maneira simples e eficiente para controlar e gerenciar os itens de estoque em uma aplicação de pequeno porte. O sistema utiliza **JDBC (Java Database Connectivity)** para se comunicar com o banco de dados **SQLite**, permitindo realizar operações básicas de CRUD (criar, ler, atualizar e deletar) nos produtos.

## Funcionalidades

O sistema permite ao usuário realizar as seguintes operações:

- **Cadastro de produtos**: Adicionar novos produtos ao estoque com informações como nome, descrição, quantidade e preço.
- **Consulta de produtos**: Pesquisar produtos no estoque por critérios como nome, código ou categoria.
- **Atualização de produtos**: Editar informações de produtos existentes no estoque, como quantidade e preço.
- **Remoção de produtos**: Excluir produtos do estoque que não são mais necessários.

O sistema também permite a visualização do estoque atual, com a listagem de todos os produtos cadastrados, e oferece uma interface simples de linha de comando para interagir com o usuário.

## Tecnologias Utilizadas

- **Java**: A linguagem de programação principal para implementar a lógica do sistema e interagir com o banco de dados.
- **JDBC**: A tecnologia utilizada para conectar o sistema com o banco de dados SQLite, permitindo que o sistema execute operações SQL (inserir, atualizar, consultar e excluir).
- **SQLite**: Banco de dados relacional utilizado para armazenar as informações dos produtos no estoque. O banco de dados é leve e não requer instalação de servidores adicionais.
- **Maven**: Utilizado como ferramenta de build e gerenciamento de dependências, facilitando a organização do projeto e a instalação de bibliotecas necessárias.
