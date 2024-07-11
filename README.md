# Plann.er

![banner](./banner.jpg)

Projeto criado com a [Rocketseat](https://www.linkedin.com/school/rocketseat/) com a professora [Fernanda Kipper](https://www.linkedin.com/in/fernanda-kipper/) na trilha de Java.

## Descrição

O **Plann.er** é uma aplicação para planejamento colaborativo de viagens. Ele permite que os usuários criem e gerenciem listas de atividades, compartilhem links importantes e monitorem a participação dos convidados. 

## Funcionalidades

- **Confirmação de participação**: Permite que os convidados confirmem sua participação na viagem.
- **Gestão de atividades**: Criação e atualização do status das atividades planejadas.
- **Compartilhamento de links**: Possibilidade de inserir links úteis para a viagem.

## Estrutura do Projeto

O projeto utiliza o framework Spring Boot e é composto por várias entidades principais:

- **Trip**: Representa uma viagem.
- **Participant**: Representa um participante da viagem.
- **Activity**: Representa uma atividade planejada para a viagem.
- **Link**: Representa um link importante relacionado à viagem.

## Dependências Utilizadas

- **Spring Data JPA**: Para operações com banco de dados.
- **Spring Web**: Para construção de aplicações web, incluindo API RESTful.
- **Flyway**: Para migrations de banco de dados.
- **Spring Boot DevTools**: Para recursos de desenvolvimento.
- **H2 Database**: Banco de dados em memória para desenvolvimento e testes.
- **Lombok**: Reduzir o código padrão gerando getters, setters, e outros métodos.
- **Spring Boot Starter Test**: Para testar aplicações Spring Boot.

---

Este projeto foi desenvolvido para oferecer uma solução prática e eficiente para o planejamento colaborativo de viagens, facilitando a organização e o engajamento dos participantes.

---

### Instalação e Configuração

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/plann.er.git
```
2. Navegue até o diretório do projeto:
```sh
  cd plann.er
```
3. Configure o banco de dados no arquivo **`application.properties`**.
4. Execute as migrations do Flyway para configurar o banco de dados:
```sh
./mvn flyway:migrate
```
5. Inicie a aplicação:
```sh
./mvnw spring-boot:run
```
6. Acesse a aplicação no navegador:
```sh
http://localhost:8080
```

---
#### Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

---
Este projeto foi desenvolvido como parte do curso de Java da Rocketseat, proporcionando uma experiência prática e aplicável em desenvolvimento de aplicações Spring Boot.
