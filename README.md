# 🛒 Projeto-Conceitual-de-banco-de-dados-E-commerce

Este repositório contém o **modelo lógico** de banco de dados para um sistema de **e-commerce**, desenvolvido como parte do laboratório da DIO: **"Refinando um Projeto Conceitual de Banco de Dados - E-commerce"**.

O arquivo foi criado utilizando o **MySQL Workbench** e representa a transição do modelo conceitual (diagrama ER) para o modelo lógico relacional, pronto para ser implementado em um SGBD como o MySQL.

## 📦 Arquivo incluído

- `E-commerce.mwb`: modelo lógico criado no MySQL Workbench.

## 🧱 Descrição Geral

O projeto representa um sistema de comércio eletrônico que inclui:

- **Clientes**: Cadastro de usuários com nome, CPF, e-mail, etc.
- **Endereços**: Um cliente pode ter múltiplos endereços.
- **Produtos**: Itens disponíveis para compra, com descrição, categoria e status.
- **Pedidos**: Registro das compras realizadas.
- **Itens do Pedido**: Quais produtos estão associados a cada pedido.
- **Pagamentos**: Informações sobre a forma e status do pagamento.
- **Entregas**: Detalhes de envio dos pedidos.
- **Estoque**: Controle de quantidade disponível por produto.
- **Categorias**: Classificação dos produtos.

## 🔗 Relacionamentos

- Relacionamento entre cliente e pedido (1:N).
- Pedido e produto possuem relacionamento via uma tabela intermediária (pedido_item).
- Produtos pertencem a uma ou mais categorias.
- Cada pedido pode ter uma entrega e um pagamento associados.

## 🛠️ Ferramentas Utilizadas

- [MySQL Workbench](https://www.mysql.com/products/workbench/)
- [DIO - Digital Innovation One](https://www.dio.me/)

## ✅ Como usar

1. Instale o [MySQL Workbench](https://dev.mysql.com/downloads/workbench/).
2. Abra o arquivo `E-commerce.mwb`.
3. Visualize, edite ou exporte o modelo para gerar o script SQL.
4. Execute o script no seu servidor MySQL.

## 🚀 Objetivo do Projeto

- Praticar modelagem lógica de banco de dados.
- Refletir regras de negócio reais de um sistema de vendas online.
- Criar uma base sólida para implementação em SQL.
