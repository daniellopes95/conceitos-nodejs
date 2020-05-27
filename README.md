<h1 align="center">Conceitos de Node.js<h1>
  
<p align="center">
  <a href="#introdução">Introdução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#desenvolvendo-a-aplicação">Desenvolvendo a Aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#"></a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>
  
## Introdução

Esse projeto é referente ao "Desafio 2" do Bootcamp GoStack by RocketSeat, que pode ser acessado por meio desse **[link](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/desafio-conceitos-nodejs)**.

A proposta do desafio é desenvolver uma aplicação em Node.js, utilizando a base CRUD (as 4 operações básicas de desenvolvimento: "Create", "Read", "Update", "Delete", ou basicamente "Inserir", "Consultar", "Alterar", "Excluir"), para controle de repositórios, além de um contole de "Likes" de cada um deles. Tudo isso, utilizando os conceitos a aprendizados passados nas aulas do bootcamp.

## Desenvolvendo a Aplicação

Iniciamos a aplicação importanto a dependência `express` para uma variável, por meio da do código **`const express = require("express");`**, que nos permite criar e definir rotas que nós darão diferentes retornos. Com isso, podemos criar a aplicação definindo a variável `app` atribuida a função `express` por meio do código **`const app = express();`**.

### Métodos HTTP (Rotas)

- #### GET (Consultar)

A função GET é responsável por consultar os repositórios armazenados do array `repositories`, retornar todos os seus registros.
