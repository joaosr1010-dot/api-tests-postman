# Projeto Prático de Testes de API – Postman

## 📖 Sobre o projeto

Este projeto foi desenvolvido como atividade prática durante meus estudos para atuar como QA Jr.  
O objetivo foi praticar testes manuais de API utilizando o Postman, aplicando conceitos de REST e métodos HTTP.  
A API utilizada foi a pública **JSONPlaceholder**: [https://jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com)


## 🔎 Endpoints testados

### 1️⃣ GET – Listar todos os usuários

https://jsonplaceholder.typicode.com/users


### 2️⃣ GET – Buscar usuário por ID

https://jsonplaceholder.typicode.com/users/1


### 3️⃣ POST – Criar usuário

https://jsonplaceholder.typicode.com/users

Body (JSON):

{

  "name": "Joaquim",
  
  "username": "teste",
  
  "email": "teste@email.com"
  
}

### 4️⃣ PUT – Atualizar usuário
https://jsonplaceholder.typicode.com/users/1

 Body (JSON):
 
{

  "name": "Leanne Grapan",
  
  "username": "Lea",
  
  "email": "teste@email.com"
  
}

### 5️⃣ DELETE – Deletar usuário
https://jsonplaceholder.typicode.com/users/1


### ⚠️ Cenário Negativo Testado

## GET Usuário inexistente (teste negativo)
https://jsonplaceholder.typicode.com/users/9999

Resultado esperado: 404 Not Found

Resultado obtido: 404 Not Found ✅

Observação: API retorna corretamente o status de recurso inexistente


## 🛠 Ferramentas utilizadas

Postman

GitHub

## 📚 Conceitos aplicados

REST

Status code

Métodos HTTP (GET, POST, PUT, DELETE)

Testes manuais de API

Testes positivos e negativos

Estruturação de Collections

Estrutura do JSON


## 💡 Observações

O Objetivo desse projeto foi demonstrar:

Organização de requests em Collection

Capacidade de identificar cenários negativos

Documentação clara e objetiva

----

### 📂 Projeto completo disponível no GitHub: https://github.com/joaosr1010-dot/api-tests-postman


