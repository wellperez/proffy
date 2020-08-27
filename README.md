<h1 align="center">
    <img alt="Proffy" src="web/src/assets/images/landing.svg" height="100px" />
    <br>Next Level Week #2<br/>
    Node.js | ReactJS | React Native
</h1>

<div align="center">

<!-- Links -->

[Rocketseat]: https://rocketseat.com.br/
[React]: https://reactjs.org/
[TypeScript]: https://www.typescriptlang.org/
[NodeJS]: https://nodejs.org/en/
[Yarn]: https://yarnpkg.com/
[ReactNative]: https://reactnative.dev/
[Expo]: https://expo.io/
[Express]: https://expressjs.com/
[DotEnv]: https://github.com/motdotla/dotenv
[Knex]: http://knexjs.org/
[Commitlint]: https://github.com/conventional-changelog/commitlint
[VSCode_Plugin_SQLite]: https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite
[Axios]: https://github.com/axios/axios

<!-- Badges -->

[BADGE_LICENSE]: https://img.shields.io/github/license/x0n4d0/proffy
[BADGE_WEB_REACT]: https://img.shields.io/badge/web-react-blue
[BADGE_MOBILE_REACT_NATIVE]: https://img.shields.io/badge/mobile-react%20native-blueviolet
[BADGE_SERVER_NODEJS]: https://img.shields.io/badge/server-nodejs-important
[BADGE_OPEN_SOURCE]: https://badges.frapsoft.com/os/v1/open-source.png?v=103
[BADGE_NODE_VERSION]: https://img.shields.io/badge/node-12.18.0-green
[BADGE_NPM_VERSION]: https://img.shields.io/badge/npm-6.14.4-red
[BADGE_OPEN_ISSUES]: https://img.shields.io/github/issues/x0n4d0/proffy?color=green
[BADGE_CLOSED_ISSUES]: https://img.shields.io/github/issues-closed/x0n4d0/proffy?color=red
[BADGE_STARS]: https://img.shields.io/github/stars/x0n4d0/proffy?style=social
[BADGE_FORKS]: https://img.shields.io/github/forks/x0n4d0/proffy?style=social

![BADGE_LICENSE] ![BADGE_WEB_REACT] ![BADGE_MOBILE_REACT_NATIVE] ![BADGE_SERVER_NODEJS] ![BADGE_OPEN_SOURCE] ![BADGE_NODE_VERSION] ![BADGE_NPM_VERSION]
</div>

## :bookmark: Sobre

O **Proffy** é uma aplicação Web/Mobile feita para auxiliar na conexão entre os alunos e os professores. Ela oferece aos professores a possibilidade de registrar aulas, podendo adicionar informações como a disciplina, o custo e horário e aos alunos, possibilitando buscar aulas cadastradas.
  
Este projeto foi idealizado pensando no **6 de agosto**, onde se comemora o **Dia Nacional dos Profissionais da Educação**.
  
Projeto Open Source desenvolvido na #NextLevelWeek da [Rocketseat], utilizando **TypeScript**, **React**, **React Native** e **Node**. 

## :rocket: Tecnologias

-  [Typescript](https://www.typescriptlang.org/)
-  [Node.js](https://nodejs.org/en/)
-  [ReactJS](https://reactjs.org/)
-  [React Native](http://facebook.github.io/react-native/)
-  [Expo](https://expo.io/)
-  [Express](https://expressjs.com/)
-  [axios](https://github.com/axios/axios)

## :octocat: Como Executar

- ### **Pré-requisitos**

  - É **necessário** possuir o **[Node.js](https://nodejs.org/en/)** instalado no computador
  - É **necessário** possuir o **[Git](https://git-scm.com/)** instalado e configurado no computador
  - Também, é **preciso** ter um gerenciador de pacotes seja o **[NPM](https://www.npmjs.com/)** ou **[Yarn](https://yarnpkg.com/)**.
  - Por fim, é **essencial** ter o **[Expo](https://expo.io/)** instalado de forma global na máquina


1. Faça um clone do repositório:

```sh
  $ git clone https://github.com/HigorSnt/proffy.git
```

2. Executando a Aplicação:

```sh
  # API
  $ cd server
  # Instalando as dependências do projeto.
  $ yarn # ou npm install
  # Configurando o banco de dados e criando as tabelas.
  $ yarn knex:migrate # ou npm run knex:migrate

  # Inicie a API
  $ yarn start # ou npm start

  # Aplicação web
  $ cd web
  # Instalando as dependências do projeto.
  $ yarn # ou npm install
  # Inicie a aplicação web
  $ yarn start # ou npm start

  # Aplicação mobile
  $ cd mobile
  # Instalando as dependências do projeto.
  $ yarn # ou npm install
  # Inicie a aplicação mobile
  $ yarn start # ou npm start
```

<h3 align="center">
Feito com ❤️ por <a href="https://www.linkedin.com/in/wellperez/">Wellington Perez</a>
<br><br>
<a href="https://rocketseat.com.br/">
  <img alt="Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1">
</a>
</h3>
## :memo: Licença

MIT [LICENSE](LICENSE.md)

---
<sup>Projeto desenvolvido com a tutoria de [Diego Fernandes](https://github.com/diego3g), da [Rocketseat](rocketseat.com.br).</sup>

