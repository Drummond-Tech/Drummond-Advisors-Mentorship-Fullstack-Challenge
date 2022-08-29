# Teste FullStack Developer Drummond Tech

## O que deverá ser desenvolvido?

Você deverá desenvolver uma lista de tarefas com todas as operações de CRUD (Create, Read, Update e Delete), utilizando um banco de dados No-SQL, além de desenvolver o Front-End da aplicação utilizando a biblioteca React.
### Detalhes: 
Front-End: React _*Preferível o uso de tailwind_
Back-End: Node + Typescript
Banco de Dados: NoSQL (Firestore ou Mongo) *Preferível o uso do Firebase

### Níveis:
`1 - CRUD simples e Layout responsivo` <br />
`2 - Cadastro e login de usuários e conexão com banco de dados` <br />
`3 - Testes automatizados e CI/CD`

### Objetivo:
Demonstrar conhecimentos em desenvolvimento FullStack, criando um banco de dados, criando e consumindo uma API e desenvolvimento do Front-End da aplicação.

### Requisitos:
**`Nível 1:`** Eliminatório (caso não consiga finalizar)

 - Realizar o pull do projeto no GIT
 - O usuário deverá ser capaz de realizar o CRUD de tarefas pelo Front-End da aplicação.
    - Criar;
    - Visualizar;
    - Editar;
    - Deletar;
- Criação de telas responsivas. (O layout não deverá quebrar quando visto em dispositivos móveis).
- Subir o projeto rodando no GitHub Pages ou Vercel.

**`Nível 2:`** Realizar cadastro de um novo usuário (Firebase) - Sign Up

- O usuário deverá ser capaz de cadastrar um novo usuário utilizando e-mail e senha (ou outra forma de login), e tal cadastro deverá ser salvo no banco de dados.
    - Caso não seja possível cadastrar um novo usuário, a aplicação deverá retornar uma tratativa.
- Realizar Login como um usuário cadastrado (Firebase) - Sign In
    - O usuário deverá ser capaz de realizar Login com um e-mail cadastrado. Caso não seja encontrado nenhum usuário, a aplicação deverá retornar uma tratativa.
    - Após realizar o Login, a aplicação deverá retornar ao usuário todas as tarefas cadastradas por ele. Caso não seja encontrada nenhuma tarefa, a aplicação deverá retornar uma tratativa.
- Criação do banco de dados de tarefas CRUD;
    - Registro das tarefas no banco de dados;
    - Visualização/Leitura da lista de tarefas;
    - Atualização das informações no banco;
    - Exclusão das informações;

**`Nível 3:`** Testes e CI/CD
- Criação de testes para o Back-End
    - Unitários
    - Integração
- Criação de processo de CI/CD para deploy automatizado e testável através de Pull Requests no Git

O layout do Front-End é por sua conta! Liberte sua imaginação e criatividade!

`Os níveis 2 e 3 não são obrigatórios, mas valem pontos de avaliação.`

Sinta-se a vontade para fazer mais do que os requisitos obrigatórios. Que tal implementar testes, ou até mesmo filtros para as tarefas?
