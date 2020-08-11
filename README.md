<!-- VARS -->

[logo-url]: https://camo.githubusercontent.com/74c8681f6d4521903b63e79173a72f0b849243be/68747470733a2f2f692e696d6775722e636f6d2f73356c546465502e706e67
[web-badge]: https://img.shields.io/badge/WEB-6842C2?logo=typescript&logoColor=47248F&label=Proffy&labelColor=6842C2&style=for-the-badge
[backend-badge]: https://img.shields.io/badge/BACKEND-04D361?logo=Node.js&logoColor=03A14A&label=Proffy&labelColor=04D361&style=for-the-badge
[mobile-badge]: https://img.shields.io/badge/MOBILE-494949?logo=react&logoColor=161616&label=Proffy&labelColor=494949&style=for-the-badge

<!-- VARS -->

<div align="center">

# ![Proffy][logo-url]

### Plataforma de estudos online, onde é possivel conectar alunos com professores.
[![web][web-badge]](#desktop_computer-web)
[![backend][backend-badge]](#globe_with_meridians-server)
[![mobile][mobile-badge]](#iphone-mobile)

![](https://raw.githubusercontent.com/lcassiol/reactjs-proffy/d2520a09b3918bf260cc8f44a731f6be24bf55e3/src/assets/images/landing.svg)

</div>

---


<div align="center">

# :globe_with_meridians: _**Server**_

</div>

### Tecnologias 
- [**NodeJS**](https://nodejs.org/) 
- [**Typescript**](https://www.typescriptlang.org/)
- [**SQLite3**](https://sqlite.org/) 
- [**Knex**](http://knexjs.org/)
- [**Express**](http://expressjs.com/)

## :pencil2: Funcionalidades

### Conexões

- _Rota para lista o total de conexões realisadas._
- _Rota para criar uma nova conexão._

### Aulas

- _Rota para criar uma aula._
- _Rota para listar aulas._
  - _Filtrar por matéria, dia da semana, e horário._

## :arrow_forward: **Passos para rodar **

_com **yarn**_

```bash
# Clonar o projeto
$ git clone https://github.com/lcassiol/nodejs-proffy.git

# Instalar dependências
$ yarn

# Criar banco de dados
$ yarn knex:migrate

# Iniciar servidor de desenvolvimento
$ yarn start
```

> O Banco de Dados fica salvo em [`src/database/database.sqlite`](src/database/database.sqlite)

> O endereço padrão do servidor Node é [`http://localhost:3333`](http://localhost:3333) podendo ser alterado no arquivo /src/server.ts

---
