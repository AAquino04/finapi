<h1 align="center">FinAPI</h1>

---

## Projeto
FinAPI é uma API desenvolvida para simular um sistema bancário simples.</p>

---

## Tecnologias
Esse projeto foi desenvolvido usando as seguintes tecnologias:
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)

---

## Execução

- Clone o repositório</li>
- Execute o comando `yarn` para baixar as dependências do projeto
- Execute o comando `yarn dev` para iniciar a aplicação
  
A aplicação estará disponível em `http://http://localhost:3333`

---

### Requisitos

- [x] Deve ser possível criar uma conta
- [x] Deve ser possível obter dados da conta do cliente
- [x] Deve ser possível atualizar dados da conta do cliente
- [x] Deve ser possível deletar uma conta
- [x] Deve ser possível realizar um depósito
- [x] Deve ser possível realizar um saque
- [x] Deve ser possível buscar o extrato bancário do cliente
- [x] Deve ser possível buscar o extrato bancário do cliente por data
- [x] Deve ser possível consultar o saldo (balance) da conta

---
### Regras de negócio

- [x] Não deve ser possível cadastrar uma conta com CPF já existente
- [x] Não deve ser possível fazer depósito em uma conta não existente
- [x] Não deve ser possível buscar extrato em uma conta não existente
- [x] Não deve ser possível fazer saque em uma conta não existente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente
- [x] Não deve ser possível excluir uma conta não existente
