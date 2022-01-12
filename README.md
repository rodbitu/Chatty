<h1 align="center">
    Chatty | NLW#5
</h1>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=000000">

 <img src="https://img.shields.io/static/v1?label=NLW&message=05&color=8257E5&labelColor=000000" alt="NLW 05" />
</p>

<br>

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [Typescript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Socket.io](https://socket.io/)
- [Sqlite](https://www.sqlite.org/index.html)

## 💻 Projeto

O Chatty é um chat para atendimento de clientes em tempo real.

## 🚀 Como executar

- Clone o repositório
- Caso ainda não tenha o arquivo `database.sqlite` dentro da pasta `src/database`, crie esse arquivo e rode `yarn typeorm migration:run` para criar as tabelas do banco de dados.
- Rode o `yarn dev` para iniciar a aplicação.
- Acesso localhost Cliente: http://localhost:3333/pages/client
- Acesso localhost Admin: http://localhost:3333/pages/admin

## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
