# [Trybe](https://www.betrybe.com/) Project - All For One

## 💻 Project

Creation of queries in SQL using DDL(Data Definition Language), DML(Data Manipulation Language) and DQL(Data Query Language) commands.

## 🚀 Built With

> [![MySQL][MySQL]][MySQL-url]

## 📌 Skills

- Use DDL, DML and DQL commands in SQL;
- Create queries for searching and filtering data;
- Create queries for inserting, updating and removing data.

## Getting Started

### ⬇️ Dependencies

```bash
npm install
cd docker
``` 

### ⚡ Running the Aplication

Initially build the back-end, front-end and test images:

```bash
docker image build -t todobackend ./todo-app/back-end
docker image build -t todofrontend ./todo-app/front-end
docker image build -t todotests ./todo-app/tests
```
Then orchestrate the containers:

```bash
npm start
``` 

## 💬 Contact Me

<div align="left" style="display: inline_block">
  <a href="https://arthur-debiasi.github.io" target="_blank"><img height="28rem" src="https://img.shields.io/badge/my_portfolio-3fc337?style=for-the-badge" target="_blank"></a> 
  <a href="https://www.linkedin.com/in/arthur-debiasi" target="_blank"><img height="28rem" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> 
  <a href = "mailto:arthurdebiasi@hotmail.com"><img height="28rem" src="https://img.shields.io/badge/outlook-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" target="_blank"></a>
</div>

<!-- ## 📄 Licença

Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE.md) para mais detalhes.

[⬆ Voltar ao topo](#nome-do-projeto)<br> -->


[Bash]: https://img.shields.io/badge/GNU_bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white
[Bash-url]: https://www.gnu.org/software/bash/
[Javascript]: https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white
[Javascript-url]: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[React-Redux.js]: https://img.shields.io/badge/react_redux-764ABC?style=for-the-badge&logo=redux&logoColor=white
[React-Redux-url]: https://react-redux.js.org/
[Docker]: https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white
[Docker-url]: https://www.docker.com/
[MySQL]: https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white
[MySQL-url]: https://dev.mysql.com/doc/
