<div align="center" style="margin-bottom: 20px;">
<img alt="gobarber" src="./img/logo.png" width="auto" heigth="auto"/>
</div>

<div align="center" style="margin: 20px;">

<p align="center" >
  <a href="#fire-prévia-da-aplicação"> :haircut: Prévia da Aplicação</a> |
  <a href="#rocket-tecnologias-usadas"> :rocket: Tecnologias Usadas</a> |
  <a href="#hammer-deploy-da-aplicação"> :hammer: Deploy da Aplicação</a> |
  <a href="#thinking-como-contribuir?"> :thinking: Como Contribuir?</a> |
  <a href="#zap-executando-o-projeto"> :zap: Executando o Projeto </a> 
</p>

</div>

## :computer: O projeto

O projeto é uma aplicação que tem como objetivo armazenar o agendamentos e grenciar serviços de beleza,
na aplicação pode-se cadastrar o prestador de serviço que terá a sua disposição uma interface web :computer: e o 
usuário que poderá agendar com os prestadores por meio de uma intreface mobile :phone:.

## :haircut: Pŕevia da Aplicação

<div align="center"> 
<img src="https://media.giphy.com/media/Lm6bmg75wR7Llcf9JG/giphy.gif" alt="preview"/>
</div>

### :rocket: Tecnologias Usadas

O projeto foi feito com as seguintes tecnologias:

- [NodeJS](https://nodejs.org/en/)
- [ReactJS](https://pt-br.reactjs.org/)
- [ExpressJS](https://expressjs.com/pt-br/)
- [JWT](https://jwt.io/)
- [Yup](https://github.com/jquense/yup)
- [Styled-Components](https://styled-components.com/)
{...}

## :hammer: Deploy da Aplicação
{...}


## :thinking: Como Contribuir?
**Faça um fork deste repositório**

```bash
# Clone o seu fork
$ git clone url-do-seu-fork && cd GoBarber

# Crie uma branch com sua feature ou correção de bugs
$ git checkout -b minha-branch

# Faça o commit das suas alterações
$ git commit -m 'feature/bugfix: minhas alterações'

# Faça o push para a sua branch
$ git push origin minha-branch
```

Depois que o merge da sua pull request for feito, você pode deletar a sua branch.

## :zap: Executando o Projeto
#### Clonando o projeto
```sh
$ git clone https://github.com/rafaelMagNunes/GoBarber.git gobarber
$ cd gobarber
```
#### Iniciando a API
```sh
$ cd api

# Criando a imagem Docker do banco de dados:
# Dentro do projeto, já existe uma arquivo docker-compose.yml que possui o
# PostgreSQL como banco de dados, basta ter o Docker instalado em sua máquina.
$ docker-compose up -d # Iniciará em background e não irá bloquear o shell

# Rodando as migrations para o banco de dados e iniciando o projeto
$ yarn
$ yarn typeorm migration:run 
$ yarn dev:server
```

#### Iniciando o Frontend
```sh
$ cd web
$ yarn 
$ yarn start
```
#### Iniciando o Mobile(Android)
```sh
$ cd mobile
$ yarn 
$ yarn android 
$ yarn start
```

### :memo: Licença

Este projeto é desenvolvido sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para saber mais detalhes.
