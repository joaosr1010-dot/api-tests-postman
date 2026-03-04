Este projeto foi desenvolvido como atividade prática durante meus estudos para atuar como QA Jr.
O objetivo foi praticar testes manuais de API utilizando o Postman, aplicando conceitos de REST e métodos HTTP.
A API utilizada foi:
https://jsonplaceholder.typicode.com/


* Endpoints testados

 1. GET – Listar todos os usuários
https://jsonplaceholder.typicode.com/users

 2. GET – Buscar usuário por ID
https://jsonplaceholder.typicode.com/users/1

 3. POST – Criar usuário
https://jsonplaceholder.typicode.com/users
Body:
{
  "name": "João Silva",
  "username": "joaosilva",
  "email": "joao@email.com"
}

 4. PUT – Atualizar usuário
https://jsonplaceholder.typicode.com/users/1
Body:
{
  "name": "João Atualizado",
  "username": "joaosilva",
  "email": "joao@email.com"
}

 5. DELETE – Deletar usuário
https://jsonplaceholder.typicode.com/users/1

6. GET – Usuário inexistente (Teste Negativo)
https://jsonplaceholder.typicode.com/users/9999
•	Resultado esperado: 404 Not Found
•	Resultado obtido: 404 Not Found 
•	Observação: API retorna corretamente o status de recurso inexistente.


Ferramentas utilizadas:
•	Postman
•	GitHub

📚 Conceitos aplicados:
•	REST
•	Métodos HTTP (GET, POST, PUT, DELETE)
•	Testes manuais de API
•	Testes positivos e negativos
•	Estruturação de collections

