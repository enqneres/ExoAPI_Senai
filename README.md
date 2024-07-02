#### Documentação feita via API Postman 

https://api.postman.com/collections/12969790-0f9f9067-2ec3-4290-aede-3fe7ffe034ad?access_key=PMAT-01J1AJ110DY8A0Q5FXQ43NKP8D

#### Exo API - Senai

##### CRUD PROJETOS

- GET - listar projetos
https://localhost:7154/api/projetos
 

- POST - cadastrar projeto
https://localhost:7154/api/projetos/

```JSON
{
"nomeDoProjeto": "Projeto D - Senai FIT",
"area": "Saúde",
"status": true
}
```


- GET - listar projeto por ID
https://localhost:7154/api/projetos/2


- PUT - atualizar projeto por ID
https://localhost:7154/api/projetos/4

```JSON
{
"nomeDoProjeto": "Projeto D - Senai Games",
"area": "Entretenimento",
"status": false
}
```

- DELETE - deletar projeto por ID
https://localhost:7154/api/projetos/4

- GET - listar projetos
https://localhost:7154/api/projetos
 

- POST - cadastrar projeto
https://localhost:7154/api/projetos/

```JSON
{
"nomeDoProjeto": "Projeto D - Senai FIT",
"area": "Saúde",
"status": true
}
```

##### CRUD USUARIOS

- GET - listar usuarios
https://localhost:7154/api/usuarios/


- POST - cadastrar usuarios
https://localhost:7154/api/usuarios/

```JSON
{
"email": "email_tres@sp.br",
"senha": "1234"
}
```

- PUT - atualizar usuarios
https://localhost:7154/api/usuarios/3

```JSON
{
"email": "email_quatro@sp.br",
"senha": "4321"
}
```

- DELETE - deletar usuario
https://localhost:7154/api/usuarios/3