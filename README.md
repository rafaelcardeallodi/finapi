<h1 align="center">FinAPI - Financeira (Node.js)</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-requisitos-e-regras-de-negocio">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=00875f&labelColor=000000">
  <img src="https://img.shields.io/static/v1?label=Rocketseat&message=Ignite&color=00875f&labelColor=000000" alt="Ignite" />
</p>

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Express](https://expressjs.com/pt-br/)

## 💻 Projeto

É um backend de uma aplicação para controle financeiro de um banco.

Este é um projeto desenvolvido durante a [Ignite](https://www.rocketseat.com.br/ignite) da Rocketseat.

## 🚀 Como executar

- Clone o repositório e acesse a pasta;
- Instale as dependências com `yarn`;
- Inicie o servidor com `yarn dev`;

A aplicação pode ser acessada em [`localhost:3333`](http://localhost:3333).

## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📄 Requisitos e Regras de Negocio

#### Requisitos

- [x] Deve ser possível criar uma conta
- [x] Deve ser possível buscar o extrato bancário do cliente
- [x] Deve ser possível realizar um depósito
- [x] Deve ser possível realizar um saque
- [x] Deve ser possível buscar o extrato bancário do cliente por data
- [x] Deve ser possível atualizar dados da conta do cliente
- [x] Deve ser possível obter dados da conta do cliente
- [x] Deve ser possível deletar uma conta
- [x] Deve ser possível retornar o balanço

---

#### Regras de negócio

- [x] Não deve ser possível cadastrar uma conta com CPF já exístente
- [x] Não deve ser possível buscar extrato em uma conta não exístente
- [x] Não deve ser possível fazer depósito em uma conta não exístente
- [x] Não deve ser possível fazer saque em uma conta não exístente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente
- [x] Não deve ser possível excluir uma conta não exístente

---

Feito com ♥ by Rafael Lodi 👋🏻
