# Testes de performance com k6

<h1 align="left">
    <img src=".github/logo-stiker.svg" width="250px">
</h1>

# User API
## Requisitos não funcionais
### Cadastro

- [ ] O cadastro com sucesso deve ocorrer em até 2 segundos
- [ ] Cadastros sem sucesso devem ocorrer em até 2 segundos
- [ ] Deve poder consultar até 100 usuários simultâneos
- [ ] A margem de erro deve ser de pelo menos 1%

## Tecnologias

- [Node.js] - plataforma de desenvolvimento
- [Express] - framework onde a API foi construída
- [MongoDB] - Banco de dados (Não relacional)
- [k6] - ferramenta para teste de carga, performance, stress etc...

## Como executar o projeto

[Node.js](https://nodejs.org/) v16 ou superior para executar.

Para liberar o gerenciador de pacotes Yarn:

```
corepack enable
```
Execute os comandos abaixo para instalar das dependências do projeto:
```sh
cd curso-k6-basico/api
yarn install
yarn dev
```
