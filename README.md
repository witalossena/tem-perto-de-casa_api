## Descrição

API RestFull de ecommerce criada com o intuito de estudo.

APi com os seguintes metódos:

* cadastro de usuario com geração de token jwt
* cadastro de lojas, produtos e categorias
* retorno de loja por categorias e usuários.

Api encontra-se hospedada no heroku [aqui](https://tpdc.herokuapp.com/)


## Tecnologias usadas neste projeto

* Adonis.js (4.1)
* node
* mySql

## Scritps

Após configurar o arquivo .env com as informação do seu banco de dados, no diretório do projeto você pode rodar:

```js
 npm install & adonis serve --dev
```

### Migrations

Rode o comando abaixo para instalar os tabelas no banco de dados..

```js
adonis migration:run
```
