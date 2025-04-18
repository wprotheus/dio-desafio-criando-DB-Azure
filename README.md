# DIO - Trilha Java Básico

## Autor

🔸[wprotheus](https://github.com/wprotheus)

---

## Desafio - Configurando uma instância de Banco de Dados na Azure  

Atividade executada conforme orientações abaixo, retiradas do [Descrição do Desafio](https://web.dio.me/lab/tipos-de-servico-de-nuvem-laboratorio/learning/ec17db7c-09ba-42c3-b238-c10f37eebd30)  
<small><sup>Obs.: O link acima somente é acessado através de uma conta na plataforma DIO.</sup></small>

### Descrição do Desafio

> Este laboratório tem como objetivo **praticar o processo de configuração de uma instância de Banco de Dados na plataforma Microsoft Azure.** Como entregável, o desafio proposto é a criação de um **repositório contendo resumos, anotações e dicas sobre o uso da Azure**, servindo como material de apoio para estudos e futuras implementações.  


### Objetivos de Aprendizagem  

> **Ao concluir este desafio, você será capaz de:**

>- Aplicar os conceitos aprendidos em um ambiente prático;
>- Documentar processos técnicos de forma clara e estruturada;
>- Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica.
  
### Entrega do Desafio  

> **Para concluir este desafio, você deverá:**  

>1. **Assistir a todas as vídeo-aulas**  
>Não pule nenhuma etapa! As aulas contêm informações essenciais para o sucesso do seu projeto.  

>2. **Criar um repositório público no GitHub contendo:**  
>Um arquivo `README.md` detalhado  
>Quaisquer arquivos adicionais que sejam relevantes para documentar sua experiência  
>Opcionalmente, capturas de tela relevantes organizadas em uma pasta `/images`  

>3. **Enviar o link do seu repositório** e uma breve descrição clicando no botão “Entregar Projeto”  

---  

# Azure + Banco de Dados

## Introdução

A integração da plataforma Microsoft Azure com serviços de banco de dados oferece uma infraestrutura robusta e escalável para armazenamento e gerenciamento de dados. Com uma variedade de opções de serviços, desde bancos de dados relacionais tradicionais até soluções NoSQL e data warehouses, a Azure permite que empresas e desenvolvedores implementem soluções personalizadas que atendam às suas necessidades específicas de armazenamento, processamento e análise de dados.

## Tutorial: Configurando uma Instância de Banco de Dados na Azure

### 1. Acesso ao Portal Azure

- Acesse o [Portal Azure](https://portal.azure.com) usando suas credenciais.

### 2. Criando um Grupo de Recursos

- No portal Azure, clique em **"Criar um recurso"** e procure por **"Grupo de Recursos"**.
- Crie um novo grupo de recursos, fornecendo um nome e selecionando a região desejada.

### 3. Criando uma Instância de Banco de Dados

- Dentro do grupo de recursos criado, clique em **"Adicionar"** para criar um novo recurso.
- Procure pelo tipo de banco de dados desejado, como **"Azure SQL Database"** ou **"Cosmos DB"** para NoSQL.
- Selecione o tipo de conta, como **"Single database"** para Azure SQL ou o modelo de consistência para Cosmos DB.
- Configure os detalhes específicos, como:
    - Nome da instância
    - Capacidade de armazenamento
    - Camada de serviço (Basic, Standard, Premium)

### 4. Configurando Opções Avançadas (Opcional)

- Dependendo do tipo de banco de dados, configure opções como:
    - Backup automático
    - Replicação geográfica para alta disponibilidade
    - Ajuste de configurações de desempenho

### 5. Revisão e Criação

- Revise todas as configurações.
- Clique em **"Criar"** para provisionar a instância de banco de dados.
- Aguarde a implantação. Você será notificado quando estiver concluída.

### 6. Acesso e Gerenciamento

- Após a criação, acesse sua instância pelo portal.
- Configure:
    - Firewall
    - Monitoramento de desempenho
    - Permissões de acesso

---  

## 📷 Capturas de telas

### Tela inicial da instanciação do DB:
<img src="./img_db/Tela (1).png" alt="Tela inicial criação DB" width="350px"/>  

### Tela final com o DB instanciado:
<img src="./img_db/Tela (7).png" alt="Tela final DB criado" width="350px"/>  

---

> **Nota:** Este guia cobre o básico para criação de uma instância. Para configurações específicas de produção, é recomendado explorar as opções de segurança, escalabilidade e monitoramento oferecidas pela Azure.
