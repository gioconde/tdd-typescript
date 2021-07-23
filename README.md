# tdd-typescript

Projeto base para utilizar como metodologia de desenvolvimento o TDD com TypeScript.


O projeto consiste em testar a "qualidade" do código através do ESLint enquanto o mesmo se encontra na "staged-area". Para isso, será utilizado o lint-staged.
O lint-staged será acionado pelo Husky através do hook "pre-commit", e só efetuará o commit após passar pelos testes do lint-staged e do Jest.


Configurações:
-ESLint
-Jest
-Husky
-lint-staged

Após clonar, executar ``npm install``

Testar aplicação utilizando o comando ``npm run test``
