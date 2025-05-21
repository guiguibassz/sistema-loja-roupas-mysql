
# 🧵 Sistema de Loja de Roupas com MySQL (Práticas de Estudos)

Este projeto foi desenvolvido com foco em **prática de modelagem e consultas SQL**, simulando um sistema real de uma loja de roupas, contendo controle de clientes, produtos, pedidos e estoque.

---

## 🛠️ Tecnologias utilizadas

- MySQL
- Workbench / phpMyAdmin
- dbdiagram.io (para visualização do modelo relacional)

---

## 📦 Estrutura do banco

O sistema é composto por 5 tabelas principais:

- `clientes` – cadastro de clientes
- `produtos` – lista de roupas disponíveis
- `estoque` – controle de quantidade por produto
- `pedidos` – pedidos realizados pelos clientes
- `itens_pedidos` – quais produtos e quantidades foram comprados por pedido

---

## 🔗 Relacionamentos

- Um cliente pode fazer vários pedidos
- Um pedido pode conter vários produtos
- Cada item de pedido pertence a um produto
- Cada produto possui controle individual de estoque

---

## ⚙️ Funcionalidades implementadas

- Criação completa das tabelas com chaves primárias e estrangeiras
- Inserção de dados de exemplo (clientes, produtos, pedidos)
- Trigger para atualizar o estoque automaticamente após a venda
- Consultas SQL com relatórios úteis

---

## 📊 Consultas SQL incluídas

Arquivo `consultas.sql` com:
- Produtos mais vendidos
- Pedidos por cliente
- Estoque abaixo do mínimo
- Faturamento total da loja
- Detalhamento de pedidos e itens

---

## 🧱 Diagrama Entidade-Relacionamento (DER)

Diagrama gerado com [dbdiagram.io](https://dbdiagram.io) para visualizar a modelagem do banco de dados:

![Diagrama ER](diagrama.png)

---

## 📁 Arquivos incluídos

- `schema.sql` → Criação das tabelas + inserts
- `consultas.sql` → Consultas SQL de análise
- `diagrama.png` → Modelo visual do banco
- `README.md` → Descrição do projeto

---

## 🎓 Objetivo

Este projeto tem fins didáticos e faz parte das minhas **práticas de estudos em banco de dados relacional com MySQL**.  
Ele simula a base de dados de uma loja de roupas, com foco em organização, integridade e extração de informações úteis com SQL.

---

## ✍️ Autor

Feito por Guilherme Almeida


