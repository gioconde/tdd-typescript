[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com)
[![GitHub](https://img.shields.io/github/license/gioconde/tdd-typescript)]
[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://opensource.org/)

# **TDD-TypeScript**
Projeto base para aplicações NodeJS em TypeScript, utilizando metodologia TDD.
---
---
> ## Bibliotecas e Ferramentas
* NPM
* Typescript
* Git
* Jest
* Husky
* Lint Staged
* Eslint
* Standard Javascript Style
* Rimraf
* Module-Alias
* Npm Check

> ## Instruções
* Se for utilizar gitflow, executar o comando ``git config gitflow.path.hooks .husky``.
* Após rodar ``npm install``, adicionar os hooks do husky com os comandos:
``npx husky add .husky/pre-commit "npx lint-staged"``
``npx husky add .husky/pre-push "npm run test:coverage"``