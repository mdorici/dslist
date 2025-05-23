

<div align="center"><img src="https://github.com/mdorici/dslist/blob/main/doc/IJS.png" alt="drawing" height="200"/></div>

## <div align="center">  Projeto DSList  </div>


## :computer: Descrição do projeto
Esse projeto foi desenvolvido durante o evento "Intensivão Java Spring" que ocorreu do dia 19 a 23 de Maio de 2025. O evento foi desenvolvido e ofertado pela [DevSuperior - Escola de programação](https://github.com/devsuperior) e ministrado pelo [Professor Nélio Alves](https://github.com/acenelio)
O "Intensivão Java Spring" teve por objetivo a criação de um projeto de estudo focado na programação back-end.

##

## :hammer: Tecnologias utilizadas
- Java
- Spring Boot
- Banco de dados H2
- Postgres
- Postman
- Git
- Docker
- SpringToolSuite4

 ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
 ![springboot](https://img.shields.io/badge/springboot-%6DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white)
 ![h2database](https://img.shields.io/badge/h2database-09476B.svg?style=for-the-badge&logo=h2database&logoColor=white)
 ![postgresql](https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
 ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
 ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
 ![docker](https://img.shields.io/badge/docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
 ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
 
## :chart_with_upwards_trend: Modelo conceitual

<div align="center"><img src="https://github.com/mdorici/dslist/blob/main/doc/modelo.png" alt="drawing" height="400"/></div>

## :memo: Endepoints

- **Game:**

  - **[GET] /games:** Busca todos os jogos cadastrados no sistema.
    
  - **[GET] /{id}:** Busca um jogo pelo id.
    
 
- **GameList:**
  
  - **[GET] /lists:** Busca as lista de jogos cadastradas no sistema.
    
  - **[GET] /{listId}/games:** Busca todos os jogos de uma lista.
    
  - **[POST] /{listId}/replacement:** Troca a posição dos jogos em uma lista.



**Collection Postman:** https://github.com/mdorici/dslist/blob/main/doc/DSList.postman_collection.json


## :rocket: Cronograma

- [x] **Aula 1:**
  - Conceitos:
    - Sistemas web e recursos
    - Cliente/servidor, HTTP, JSON
    - Padrão Restpara API web
  - Estruturação de projeto Spring Rest
  - Entidades e ORM
  - Databaseseeding
  - Padrão camadas
  - Controller, service, repository
  - Padrão DTO

- [x] **Aula 2:**
  - Relacionamentos N-N
  - Classe de associação, embeddedid
  - Consultas SQL no Spring Data JPA
  - Projections

- [x] **Aula 3:**
  - Dicas de currículo e portfólio
  - Perfis de projeto
  - Ambiente local com Docker Compose
  - Processo de homologação local
  - Processo de deploycom CI/CD
  - Configuração de CORS

- [x] **Aula 4:**
  - Design e implementação de endpoint especial
  - Operação de atualização no Spring
  - Operações com List
  - Verbo HTTP e idempotência

