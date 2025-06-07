# Spring Inventory System - Frontend Web

Este projeto é um **front-end web simples** (HTML, CSS, JS) para consumo da [API Spring Inventory System](https://github.com/Matheus-Marti1/spring-inventory-system-api/tree/mysql).

> **Atenção:** Esta aplicação é apenas a interface visual. Todos os dados e regras de negócio estão na API acima.

---

## Funcionalidades

- **CRUD de Clientes**  
- **CRUD de Categorias**
- **CRUD de Produtos**
- **CRUD de Pedidos**
- Busca em todas as telas
- Filtragem na tela de Pedidos

---

## Requisitos

- [Node.js](https://nodejs.org/) (opcional, apenas para rodar um servidor local se desejar)
- Uma instância rodando da [API Spring Inventory System](https://github.com/Matheus-Marti1/spring-inventory-system-api/tree/mysql) em `http://localhost:8080`  
  (ou ajuste o endereço da API nos arquivos HTML)

---

## Como usar

1. **Clone este repositório**
   ```bash
   git clone https://github.com/Matheus-Marti1/spring-inventory-system-api-front.git
   cd spring-inventory-system-api-front
   ```

2. **Inicie a API**  
   Siga as instruções do repositório da [API](https://github.com/Matheus-Marti1/spring-inventory-system-api/tree/mysql) para rodar o backend.

3. **Abra o `index.html` no navegador**  
   - Você pode apenas abrir com duplo clique, ou  
   - Rodar um servidor local (recomendado para evitar problemas de CORS, porém a API já está configurada para levar em conta apenas abrir o arquivo no navegador):

     ```bash
     # Com Node.js (http-server)
     npx http-server .
     # ou com Python 3
     python -m http.server 8081
     ```

---

### Endereço da API

O padrão é `http://localhost:8080`.  
Se você rodar a API em outro endereço/porta, ajuste as URLs nos scripts dos arquivos HTML.

---

## Tecnologias

- HTML
- CSS
- JavaScript (puro, sem frameworks)

---

## Observações

- Este projeto foi desenvolvido para fins de estudo/demonstração.
