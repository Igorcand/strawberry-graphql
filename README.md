# GraphQL project with python module Strawberry

## Sobre o Projeto ##

Este código implementa uma API GraphQL simples usando a biblioteca strawberry-graphql em Python. Ele define um esquema GraphQL com um tipo de dados Livro e Pessoa e uma Query para recuperar a lista de livros disponíveis e de pessoas cadastradas e Mutations para adicionar valores.

## Tecnologias usadas ##
- Python
- Poetry
- Strawberry
- FastAPI
- SQLite

## Como rodar ##

```bash

poetry init

poetry add fastapi uvicorn[standard] sqlmodel strawberry-graphql strawberry-graphql[cli]

poetry shell 

uvicorn app.app:app --reload

```

## Autor ##

Igor Cândido Rodrigues

https://www.linkedin.com/in/igorc%C3%A2ndido/