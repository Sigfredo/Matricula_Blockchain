# Matricula Blockchain

Projeto de matrícula em blockchain.
Vagas são disponibilizadas e os alunos podem se matricular nelas. O ato de se matricular gera uma transação de transferência de valor (vaga da disciplina para o aluno). A vaga foi criada como um smart contract.

Como rodar a aplicação (Somente Linux):

#### 1. NODEJS
Instale o nodeJS:
https://nodejs.org/en/download/package-manager/

#### 2. NPM
Certifique-se de ter a úlima versão do npm:
https://docs.npmjs.com/getting-started/installing-node

#### 3. TESTRPC
3.1 Instale o testrpc:
```Bash
npm install -g ethereumjs-testrpc
```
3.2 Execute o testrpc:
```Bash
$ testrpc
```
3.3 Deixe o testrpc rodando em um terminal. Abra outro terminal para o próximo tópico.

#### 4. TRUFFLE
4.1 Instale o Truffle:
```Bash
$ npm install -g truffle
```

### 5. APLICAÇÃO
5.1 Navegue até a pasta do projeto e execute os comandos:
```Bash
$ truffle compile
```
```Bash
$ truffle deploy
```
```Bash
$ truffle test
```
```Bash
$ truffle serve
```
5.2 Abra no navegador o endereço:

http://localhost:8080/

5.3 Informe a quantidade de vagas e o endereço da carteira do aluno a ser matriculado. Como o sistema gera endereços aleatórios, é necessário escolher um deles no terminal que está rodando o testrpc. Busque onde está escrito "Available Accounts" Escolha um dos 10 endereços.
