# PETSHOP

Projeto pessoal criado para praticar testes unitários, eslint e github actions

Desenvolvido através do curso 
[NodeJS: Adicionando CI ao projeto e deploy no Google Cloud](https://www.alura.com.br/curso-online-nodejs-adicionando-ci-projeto-deploy-google-cloud), e outras fontes.

## Programas necessários

- mysql. Versão utilizada: 14.14
- node.js
- npm

## Inicializando a base de dados

1. Insira as credenciais de acesso ao banco de dados local no arquivo ```config/default.json```. Utilize o arquivo ```config/default.example.json``` como base.
2. Execute o comando ```node api/banco-de-dados/criarTabelas.js``` para criar as tabelas necessárias

## Executando a API

1. Execute o comando ```npm install``` para instalar as dependências
2. Execute o comando ```node api/index.js```

A api estará rodando na porta **3000**

