## Estrutura do Projeto
- `order-api`: MSA - Gestão de pedidos.
  - [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&&metric=coverage)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api) [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api) [![Bugs](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&metric=bugs)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api)
- `customer-api`: MSA - Cliente
  - [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&&metric=coverage)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api) [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api) [![Bugs](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&metric=bugs)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api)
- `product-api`: MSA - Produtos.
  - [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&&metric=coverage)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api) [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api) [![Bugs](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&metric=bugs)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api)

<details>
  <summary> <h2> Entregáveis FASE 4 </h2> </summary>
  
- [x] Refatorar o projeto em 3 microsserviços
- [x] Utilizar ao menos um banco de dados NoSQL e um SQL
- [x] Os serviços devem se comunicar entre si
- [x] Os serviços devem conter testes unitários
- [x] Ao menos um dos caminhos de teste deve implementar BDD
- [x] Todo os projetos devem ter ao menos 80% de cobertura
- [x] Os repositórios precisam ser separados
- [x] A branc main precisa estar protegida
- [x] PR para branch main deve validar o build da aplicação e a qualidade de código via sonarqube ou similar
- [x] O deploy dos microsserviços precisa ter automatizado

</details>

<details>
  <summary> <h2> Descrição do projeto </h2> </summary>

O projeto fast-food-api é um sistema backend desenvolvido para fornecer uma solução robusta e escalável para o Tech Challenge da pós graduação em Software Architecture da FIAP. Ele foi projetado para atender às necessidades de controle de pedidos em uma lanchonete de bairro. 

Acesse a [Wiki do Projeto](https://github.com/tshadz-fiap-postech-soat3/soat3-tech-challenge/wiki) para mais informações a respeito dos:

* Requisitos técnicos (business)
* Domain-Driven Design
* S-SDLC
* Arquitetura

### Tecnologias Utilizadas:

- **Linguagem de Programação**: TypeScript
- **Framework**: NestJS
- **Banco de Dados**: MySQL e MongoDB
- **Serviço de Cloud**:Google Cloud Platform (GCP)
- **Ferramentas de DevOps**: GitHub Actions, Terraform e SonarCloud.

</details>

<details>
  <summary> <h2> CI/CD Pipeline </h2> </summary>

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/27eadf3f-8543-4666-bb52-10b9ddac388a

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/2d0483ab-598a-42b1-bb38-b3a61f6e101c

</details>

<details>
  <summary> <h2> Sonar Cloud </h2> </summary>

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/d6b1bfa6-e4e0-41b9-b621-c21aa9011c52

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/67262cab-4468-48ea-b1dc-a12b1c170c5a

</details>

<details>
  <summary> <h2> Database deploy </h2> </summary>
  
https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/c7aad8b9-bfaa-43c7-b206-8e38d1cd05cb

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/bb88e639-6b47-4793-9ccd-e241da364cc8

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/413cd46b-d269-46c3-881d-43ff4ad84ca2

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/be011672-5ed0-4543-8417-35303c9a7a0a

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/75b12ae5-95bb-4952-8ccc-8915807409dc

</details>

<details>
  <summary> <h2> API Deploy </h2> </summary>

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/6f1027ab-85bc-4854-a787-e702ba87885e

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/25e796bb-bdb2-4453-8a5e-e01bfae62565

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/de12941b-b78c-4637-ac25-d22fb42465ff

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/1b21ff7d-13c2-476f-bce0-0865910763fa

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/34e0f85e-5630-428c-95f9-f8d93075c526

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/701c4821-fe7b-443b-9d1e-5debbcaa8e74

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/bf9bf313-5957-4a32-9de6-d2ea2e57d501

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/caf87b0f-740b-4c95-889e-866375457c6f

</details>

<details>
  <summary> <h2> Customer API + MongoDB + auth </h2> </summary>

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/d4b8498b-53ab-4bba-abb4-b0e71cf07028

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/148071b1-d4ba-4f23-b0ab-d8718b2cf531

</details>
