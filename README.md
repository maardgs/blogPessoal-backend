# Blog Pessoal - Projeto Spring Framework

O Blog Pessoal é um projeto desenvolvido no Framework Spring durante o Bootcamp Desenvolvedor Java Fullstack da Generation Brasil. 

## Tecnologias Utilizadas

- Spring Boot
- Spring Data JPA
- Spring Security (JWT)
- Bancos de Dados Relacionais: MySQL e PostgreSQL
- Gerenciador de dependências Maven

## Recursos

### Postagem

O recurso Postagem é responsável por definir o objeto de postagem no Blog Pessoal. Ele inclui os seguintes atributos:

- `id`: Identificador único da postagem
- `titulo`: Título da postagem
- `texto`: Conteúdo da postagem
- `data`: Data de criação da postagem
- `senha`: Senha (se necessário)
- `tema`: Objeto Tema associado à postagem
- `usuario`: Objeto Usuario que criou a postagem

### Tema

O recurso Tema classifica as postagens através do objeto Tema. Ele possui os seguintes atributos:

- `id`: Identificador único do tema
- `descricao`: Descrição do tema
- `postagem`: Lista de postagens associadas a esse tema

### Usuario

O recurso Usuario define o objeto de usuário que pode acessar e criar postagens no Blog Pessoal. Ele inclui os seguintes atributos:

- `id`: Identificador único do usuário
- `nome`: Nome do usuário
- `usuario`: Nome de usuário (login)
- `senha`: Senha do usuário
- `foto`: URL da foto do usuário
- `postagem`: Lista de postagens criadas pelo usuário

### UsuarioLogin

A classe auxiliar UsuarioLogin é utilizada para efetuar login no Blog Pessoal. Ela possui os seguintes atributos:

- `id`: Identificador único do usuário
- `nome`: Nome do usuário
- `usuario`: Nome de usuário (login)
- `senha`: Senha do usuário
- `foto`: URL da foto do usuário
- `token`: Token de autenticação
