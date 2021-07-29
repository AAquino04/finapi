<h1 align="center">FinAPI</h1>

---

<h2>Projeto</h2>
  <p>FinAPI é uma API desenvolvida para simular um sistema bancário simples.</p>

---

<h2>Tecnologias</h2>
  <p>Esse projeto foi desenvolvido usando as seguintes tecnologias:</p>
  <ul>
    <li>Node.js</li>
    <li>Express</li>
  </ul>

---

<h2>Execução</h2>
  <ul>
    <li>Clone o repositório</li>
    <li>Execute o comando ```yarn``` para baixar as dependências do projeto</li>
    <li>Execute o comando ```yarn dev``` para iniciar a aplicação</li>
  </ul>
  
  <p>A aplicação estará disponível em ```http://http://localhost:3333```</p>

---

<h3>Requisitos</h3>

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

<h3>Regras de negócio</h3>

- [x] Não deve ser possível cadastrar uma conta com CPF já existente
- [x] Não deve ser possível fazer depósito em uma conta não existente
- [x] Não deve ser possível buscar extrato em uma conta não existente
- [x] Não deve ser possível fazer saque em uma conta não existente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente
- [x] Não deve ser possível excluir uma conta não existente
