## Estrutura do Projeto
- `.github`: template do CICD
- `ci-pipeline`: contém o código de integração
- `cd-pipeline`: contém o código de deploy
- `devsecops-pipeline`:  contém os testes de segurança
- `terraform-cloud-infra`:  repo responsável pelo deploy da imagem utilizando o cloud run
- `terraform-database`: repo responsável pelo deploy de todos os bancos
- `order-orchestrator-api`: repo contém o código do orquestrador de pedidos e lógica para deploy no GCP
- `order-api`: este repositório contém o código da api de pedidos e a lógica para deploy no GCP
  - [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&&metric=coverage)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api) [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api) [![Bugs](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&metric=bugs)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api)
- `customer-api`: este repositório contém o código da api de customer e a lógica para deploy no GCP
  - [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&&metric=coverage)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api) [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api) [![Bugs](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&metric=bugs)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api)
- `product-api`: este repositório contém o código da api de produtos e a lógica para deploy no GCP
  - [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&&metric=coverage)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api) [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api) [![Bugs](https://sonarcloud.io/api/project_badges/measure?project=tshadz-fiap-postech-soat3_customer-api&metric=bugs)](https://sonarcloud.io/summary/new_code?id=tshadz-fiap-postech-soat3_customer-api)

![image](https://github.com/user-attachments/assets/ef12c18c-0ba2-4270-b199-c2d44fe7cd8d)


## FASE 4 - Arquitetura de Microserviços
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
  <summary> <h2> Customer API + MongoDB </h2> </summary>

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/d4b8498b-53ab-4bba-abb4-b0e71cf07028

https://github.com/tshadz-fiap-postech-soat3/.github/assets/80704054/148071b1-d4ba-4f23-b0ab-d8718b2cf531

</details>

<details>
  <summary> <h2> User Authentication - Cloud Functions + Firebase </h2> </summary>

https://github.com/user-attachments/assets/9993a899-60ad-479e-afed-284d28f1c840

</details>

## FASE 5 - Dados e segurança da informação

<details>
  <summary> <h2> Entregáveis FASE 5 </h2> </summary>
  
- [x] Utilizar padrão SAGA para aumentar a disponibilidade da aplicação
- [x] Justificativa do padrão escolhido
- [x] Fluxos: Pagamento Aprovado e Pagamento Recusado
- [x] Utilizar gerenciador de mensageria
- [x] Executar OWASP Zap nos fluxos de Listar cardápio / Realização do Pedido / Geração do pagamento / Confirmação do Pagamento
- [x] Relatório RIPD
- [x] Rota para o cliente solicitar a exclusão/inativação de seus dados pessoais

</details>

<details>
  <summary> <h2> SAGA Pattern </h2> </summary>
  
O vídeo explicativo da implementação da SAGa Orquestrada pode ser acessado através do seguinte link:

[SAGA Orquestrada Vídeo](https://drive.google.com/file/d/1Wg2Wze2vEdpC86JXzlcyIk-llbr2Y9C3/view?usp=drive_link)

### Orquestração

1. Redução de Acoplamento:
  - Desacoplamento dos Serviços: Uma saga orquestrada ajuda a desacoplar os microsserviços, permitindo que cada um funcione de forma independente. Isso facilita a substituição ou atualização de um serviço sem afetar os demais.
  - Interação Definida: A orquestração define claramente como os serviços interagem, reduzindo a complexidade e dependência entre eles.
2. Facilidade de Manutenção e Debug:
  - Visibilidade do Fluxo de Processos: Com uma saga orquestrada, o fluxo de transações é centralizado, tornando mais fácil monitorar, depurar e entender o estado do sistema.
  - Gerenciamento de Erros: A orquestração pode tratar erros e compensações de forma centralizada, o que simplifica a identificação e a correção de problemas.
3. Custo e Eficiência:
  - Menos Mão de Obra Necessária: Automatizar o gerenciamento de transações e processos reduz a necessidade de intervenção manual e, portanto, o custo com mão de obra.
  - Serviço Terceirizado: Com serviços terceirizados e uma orquestração bem definida, a manutenção e o desenvolvimento podem ser mais facilmente gerenciados por terceiros, reduzindo custos operacionais.
4. Flexibilidade e Escalabilidade:
  - Escalabilidade Individual: Cada serviço pode ser escalado de forma independente conforme a demanda, o que é ideal para sistemas com altos volumes de pedidos e variações na carga de trabalho.
  - Adaptação a Mudanças: Mudanças nos requisitos do negócio ou na arquitetura do sistema podem ser incorporadas com menos esforço, pois a orquestração pode ser ajustada sem afetar todos os serviços.
5. Transparência e Controle:
  - Monitoramento Centralizado: A orquestração centraliza o monitoramento dos processos, proporcionando uma visão clara de todo o fluxo e facilitando a identificação de problemas ou gargalos.
  - Auditoria e Compliance: Ter um controle centralizado sobre as transações pode ajudar a garantir conformidade com regulamentos e facilitar auditorias.
6. Coerência e Consistência:
  - Gerenciamento de Estado: Uma saga orquestrada assegura que todos os passos do processo sejam gerenciados de forma coerente, garantindo a consistência dos dados e a integridade das transações.
________________________________
### Arquitetura e fluxo de dados
Diagrama da estrutura na nuvem e comunicação SAGA:

![diagrama de architetura](https://github.com/user-attachments/assets/796d299b-fa97-4c2f-8dbe-259af5bd9ebf)


![saga orquestrada](https://github.com/user-attachments/assets/281b7719-1d53-459a-93d0-b4a70b325a2c)


- Filas
  - create_order: Solicita a criação de um novo pedido.
  - order_created: Notifica que um pedido foi criado com status payment_due.
  - process_payment: Solicita o processamento do pagamento para um pedido.
  - payment_processed: Notifica que o pagamento foi processado com sucesso.
  - order_placed: Notifica que o status do pedido foi alterado para placed.
  - order_confirmed: Notifica que a cozinha confirmou o pedido.
  - order_processing: Notifica que o pedido está sendo processado pela cozinha.
  - order_ready_to_pickup: Notifica que o pedido está pronto para ser retirado.
  - order_concluded: Notifica que o pedido foi concluído após retirada pelo cliente.
  - order_cancelled: Notifica que o pedido foi cancelado.
 
- Fluxo de criação de pedidos
  - Frontend envia uma solicitação para o Orquestrador criar um pedido.
  - Orquestrador publica uma mensagem na fila create_order.
  - Microsserviço de Pedido consome a mensagem da fila create_order, cria o pedido no banco de dados com status payment_due, e publica uma mensagem na fila order_created.
  - Orquestrador consome a mensagem da fila order_created e publica uma mensagem na fila process_payment.
  - Microsserviço de Pagamento consome a mensagem da fila process_payment, processa o pagamento, e publica uma mensagem na fila payment_processed.
  - Orquestrador consome a mensagem da fila payment_processed, atualiza o status do pedido para placed, e publica uma mensagem na fila order_placed.
  - Microsserviço de Pedido consome a mensagem da fila order_placed e notifica a cozinha publicando uma mensagem na fila order_confirmed.
  - Cozinha consome a mensagem da fila order_confirmed, atualiza o status do pedido para processing, e publica uma mensagem na fila order_processing.
  - Cozinha conclui o preparo do pedido, atualiza o status para ready_to_pickup, e publica uma mensagem na fila order_ready_to_pickup.
  - Orquestrador consome a mensagem da fila order_ready_to_pickup e publica uma mensagem na fila notify_customer.
  - Cliente é notificado no telão que o pedido está pronto para retirada.
  - Balcão atualiza o status do pedido para concluded após a retirada e publica uma mensagem na fila order_concluded.

</details>

<details>
  <summary> <h2> Desenvolvimento Seguro - DevSecOps - Pipeline / OWASP Zap - Reports </h2> </summary>

A pipeline de DevSecOps para este projeto pode ser acessada através do seguinte link:

[DevSecOps Pipeline](https://github.com/tshadz-fiap-postech-soat3/devsecops-pipeline)

O vídeo explicativo da implementação da DevSecOps pipeline pode ser acessado através do seguinte link:

[DevSecOps Pipeline Vídeo](https://drive.google.com/file/d/1Wg2Wze2vEdpC86JXzlcyIk-llbr2Y9C3/view?usp=drive_link)
__________________

### DevSecOps - Pipeline

  A pipeline de segurança automatiza a detecção de vulnerabilidades em várias camadas do ciclo de desenvolvimento, desde a infraestrutura até o código e dependências, garantindo uma abordagem abrangente para a segurança do software.
  
1. IAC - Trivy:

- Trivy é uma ferramenta de scanner de segurança que verifica a infraestrutura como código (IaC) em busca de vulnerabilidades e configurações incorretas. Ele pode analisar arquivos como Dockerfile, Kubernetes, Terraform, etc., ajudando a garantir que a infraestrutura seja provisionada com segurança desde o início.

2. SAST - Semgrep:

- Semgrep é uma ferramenta de análise estática de código (SAST) que verifica o código fonte em busca de vulnerabilidades de segurança, bugs e padrões de codificação inseguros. Ele usa regras definidas para detectar problemas antes que o código seja implementado.

3. SCA - Dependency-Check:

- Dependency-Check é uma ferramenta de análise de componentes de software (SCA) que verifica as dependências de um projeto em busca de vulnerabilidades conhecidas. Ele examina bibliotecas de terceiros usadas no projeto e alerta sobre possíveis riscos.

4. DAST - OWASP ZAP:

- OWASP ZAP (Zed Attack Proxy) é uma ferramenta de teste dinâmico de segurança de aplicações (DAST). Ela simula ataques em tempo real contra uma aplicação web para identificar vulnerabilidades como injeção de SQL, cross-site scripting (XSS), entre outras.

5. Secrets - Gitleaks:

- Gitleaks é uma ferramenta que verifica repositórios Git em busca de informações sensíveis, como chaves de API, senhas e outros segredos que não devem ser expostos no código. Ela ajuda a evitar que credenciais sensíveis sejam comprometidas.
  
![image](https://github.com/user-attachments/assets/224e6e20-5ad9-48c5-8cfa-758146a02cc2)

________________________________

### DAST Reports
Aqui estão os relatórios DAST gerados para `product-api` e `order-api`:
________________________________

#### PRODUCT-API

Primeira análise:
  - <b>Link para o relatório completo na Pipeline:</b> [DevSecOps Pipeline Summary](https://github.com/tshadz-fiap-postech-soat3/product-api/actions/runs/10283732784)
  - <b>Report:</b>
  
![image](https://github.com/user-attachments/assets/13c16e0d-ece9-4dc8-90e9-ad67978e8e92)

Segunda Análise:
  - <b>Link para o relatório completo na Pipeline:</b> [DevSecOps Pipeline Summary](https://github.com/tshadz-fiap-postech-soat3/product-api/actions/runs/10283851553)
  - <b>Report:</b>

![image](https://github.com/user-attachments/assets/7b31cffe-66c3-46ba-9c5d-4df17865840c)
________________________________

#### ORDER-API

Primeira análise:
  - <b>Link para o relatório completo na Pipeline:</b> [DevSecOps Pipeline Summary](https://github.com/tshadz-fiap-postech-soat3/order-api/actions/runs/10286649139)
  - <b>Report:</b>
  
![image](https://github.com/user-attachments/assets/f55415aa-a37a-411b-9680-3d990a8e22d0)
________________________________

</details>

<details>
  <summary> <h2> Privacidade de Dados e LGPD </h2> </summary>

### RIPD - Relatório de Impacto à Proteção dos Dados Pessoais

Aqui está o relatório de impacto:

[LGPD - RIPD - PosTech-SOAT3-G68](https://docs.google.com/document/d/1VQAqVCFKz5fwItgQyFCmHVlZqSLtLnqX/edit?usp=drive_link&ouid=115953080927918010909&rtpof=true&sd=true)
________________________________

### Rota para inativação dos dados do cliente

Código para inativação dos dados do cliente no banco de dados:

```bash
await this.prisma.customer.update({
      where: { id },
      data: {
        name: 'INACTIVE_NAME',
        cpf: 'INACTIVE_CPF',
        email: 'INACTIVE_EMAIL',
        address: 'INACTIVE_ADDRESS',
  },
});
```
Demonstração da chamada para inativar os dados do cliente

https://github.com/user-attachments/assets/9f818c78-c70c-4e0a-8e71-d68ef516b6cf


</details>
