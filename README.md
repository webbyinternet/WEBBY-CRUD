# WEBBY-CRUD


# Backend
Desenvolver uma API JSON REST na *linguagem a sua escolha*, que utilize os métodos (​GET​, ​POST​, ​PUT​,
DELETE​).

# Frontend
UI/UX fica a critério do desenvolvedor porém deverá ser SPA (single-page
application) e atender o consumo de todos endpoints da API 

# Especificação
Monte uma base de pessoas com a seguinte estrutura:

```
nome: varchar
sexo: char
idade: integer
hobby: varchar
datanascimento: date
```

Utilize o ​banco de dados​ de sua preferência para armazenar os dados que a API irá
consumir.

# API endpoints

Retorna todos as pessoas
```
GET /persons
Codes 200
```

Retorna os pessoas de acordo com o termo passado via querystring e
paginação
```
GET /persons?
Codes 200 / 404
```

Retorna os dados de uma pessoa
```
GET /persons/{id}
Codes 200 / 404
```

Adiciona uma nova pessoa
```
POST /persons
Codes 201 / 400
```

Atualiza os dados de uma pessoa
```
PUT /persons/{id}
Codes 200 / 400
```

Apaga o registro de uma pessoa
```
DELETE /persons/{id}
Codes 204 / 400
```


# O que será avaliado
•	Estrutura do código
•	Lógica de programação
•	Clean Code

# Entrega
Após finalizado enviar por e-mail o link do projeto no github, com explicação no README.

