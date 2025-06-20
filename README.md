# Projeto Hospital

Este projeto é uma aplicação back-end desenvolvida em Java com Spring Boot para gerenciar informações de um hospital, incluindo dados de pacientes, médicos e consultas. O objetivo principal foi aplicar os conhecimentos adquiridos no curso de desenvolvedor back-end Java do Senai, focando em boas práticas de desenvolvimento, arquitetura de software e integração de banco de dados.

## Funcionalidades

- **Gerenciamento de Pacientes:** CRUD completo.
- **Gerenciamento de Médicos:** CRUD completo.
- **Gerenciamento de Consultas:** Agendamento, listagem, busca, atualização e exclusão.

## Tecnologias Utilizadas

As seguintes tecnologias e ferramentas foram utilizadas no desenvolvimento deste projeto:

- **Java 17**
- **Spring Boot 3.3.1**
- **Spring Data JPA**
- **Spring Web**
- **Maven**
- **H2 Database**
- **MySQL Connector/J**
- **Springdoc OpenAPI UI (Swagger UI)**

## Como Executar o Projeto

Para executar este projeto localmente, siga os passos abaixo:

### Pré-requisitos

- Java Development Kit (JDK) 17 ou superior.
- Maven 3.x ou superior.
- Git.

### Passos

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/welington-Miiller/Hospital.git
   cd Hospital
   ```

2. **Compile o projeto:**
   ```bash
   mvn clean install
   ```

3. **Execute a aplicação:**
   ```bash
   mvn spring-boot:run
   ```

   A aplicação estará disponível em `http://localhost:8080`.
   A documentação da API (Swagger UI) estará acessível em `http://localhost:8080/swagger-ui.html`.

## Estrutura do Projeto

O projeto segue uma estrutura de pacotes organizada, comum em aplicações Spring Boot, para promover a separação de responsabilidades:

```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── example/
│   │           └── demo/
│   │               ├── HospitalApplication.java         # Classe principal da aplicação
│   │               ├── controllers/                     # Camada de controle (APIs REST)
│   │               │   ├── ConsultaController.java
│   │               │   ├── MedicoController.java
│   │               │   └── PacienteController.java
│   │               ├── entities/                        # Camada de entidades (modelos de dados)
│   │               │   ├── Consulta.java
│   │               │   ├── Medico.java
│   │               │   └── Paciente.java
│   │               ├── repositories/                    # Camada de acesso a dados (Spring Data JPA)
│   │               │   ├── ConsultaRepository.java
│   │               │   ├── MedicoRepository.java
│   │               │   └── PacienteRepository.java
│   │               └── services/                        # Camada de serviços (lógica de negócio)
│   │                   ├── ConsultaService.java
│   │                   ├── MedicoService.java
│   │                   └── PacienteService.java
│   └── resources/
│       ├── application.properties                     # Configurações da aplicação
│       └── static/
└── test/
    └── java/
        └── com/
            └── example/
                └── demo/
                    └── HospitalApplicationTests.java    # Testes unitários e de integração
```

## Habilidades e Conhecimentos Adquiridos (Curso Senai)

Este projeto consolidou habilidades em:

- **Programação Orientada a Objetos (POO):** Aplicação de conceitos de POO na modelagem e estrutura do código.
- **Desenvolvimento com Spring Boot:** Configuração rápida, APIs RESTful com `Spring Web`, injeção de dependências.
- **Persistência de Dados com Spring Data JPA e Hibernate:** Mapeamento ORM, operações CRUD, relacionamentos entre entidades.
- **Modelagem de Banco de Dados Relacionais:** Design de esquema de banco de dados.
- **Boas Práticas de Código e Arquitetura:** Organização em camadas (Controller, Service, Repository, Entity), padrões de projeto, código limpo.
- **Gerenciamento de Dependências com Maven:** Gerenciamento de bibliotecas.
- **Testes Unitários e de Integração:** Escrita de testes para funcionalidade e robustez.
- **Documentação de API com OpenAPI (Swagger):** Geração automática de documentação interativa.

## Contribuição

Este projeto foi desenvolvido por:

- [Welington Miller](https://github.com/welington-Miiller)
- [Elias Ximenes](https://github.com/EliasXi)
- [Leticia Barauna](https://github.com/leticiaB24)
- [Vitor](https://github.com/Victorsszx)

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.




## Modelagem do Banco de Dados
### Banco de Dados Conceitual
![Projeto Final - Modelo Conceitual](https://github.com/user-attachments/assets/faad0bae-c289-4c4c-b17a-990927c112d2)

### Banco de Dados Lógico
![Projeto Final - Modelo Lógico](https://github.com/user-attachments/assets/2387bf90-8b08-4f87-8024-854e8b582995)

## Apresentação do Projeto
[Projeto Final - Gestão de Consultas Médicas.pdf](https://github.com/user-attachments/files/16249118/Projeto.Final.-.Gestao.de.Consultas.Medicas.pdf)


