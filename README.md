# Starter - NodeJS
Este é um projeto com a finalidade de entender conceitos do **NodeJS** na criação de uma API. O projeto foi realizado junto ao minicurso gratuito (Starter) da RocketSeat.

## Tecnologias
* CORS
* Express
* Mongoose

## Linguagens
* JavaScript

## Executar
**Para executar este projeto na sua máquina, execute os seguintes comandos no seu terminal:**
```
$ git clone https://github.com/dhayananascimento/starter-nodejs.git
$ cd starter-nodejs
$ npm install
$ npm run dev
```

## Testar Rotas

#### criar
método: POST

http://localhost:3001/api/products

json:{ "title": "**título**", "description": "**descrição**", "url": "**url**" }

#### atualizar
método: PUT

http://localhost:3001/api/products/id

json: { "title": "**novo título**", "description": "**nova descrição**", "url": "**nova url**" }

#### listar
método: GET

http://localhost:3001/api/products?page=num

#### listar específico
método: GET

http://localhost:3001/api/products/id

#### deletar
método: DEL

http://localhost:3001/api/products/id


> NOTA: 
> id => referece ao identificador do produto criado,
> num => referece ao número da página ,
> **substituir os valores do json em negrito pelos valores desejados**.


