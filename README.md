### Estrutura do Curso

#### Módulo 1: Apresentação do Projeto e Conceitos Fundamentais

1. **Aula 1: Apresentação do Projeto**
   - **Visão Geral do Projeto:**
     - Descrição do sistema de gerenciamento de eventos e venda de ingressos
     - Funcionalidades principais: CRUD de Evento, Ingresso, e Usuário
   - **Estrutura do Sistema:**
     - Arquitetura geral
     - Tecnologias e ferramentas que serão utilizadas
     - Objetivos de aprendizado

2. **Aula 2: Conceitos Básicos de Internet e Backend**
   - **Conceitos de Internet:**
     - O que é a Internet e como ela funciona
     - Protocolos HTTP e HTTPS
     - Conceito de cliente e servidor
   - **Arquitetura de Backend:**
     - O que é o backend e como ele interage com o frontend
     - Função dos servidores, APIs e bancos de dados
     - Exemplos de aplicações backend

3. **Aula 3: Introdução a APIs (Application Programming Interfaces)**
   - **O que é uma API:**
     - Definição e propósito das APIs
     - Como APIs permitem a comunicação entre diferentes sistemas
   - **Tipos de APIs:**
     - APIs RESTful vs. APIs SOAP
     - Métodos HTTP (GET, POST, PUT, DELETE)
   - **Como uma API funciona:**
     - Estrutura de uma requisição e resposta de API
     - Exemplo simples de uma requisição e resposta

4. **Aula 4: Introdução ao Spring Framework**
   - **O que é o Spring Framework:**
     - Principais módulos e objetivos
     - O papel do Spring no desenvolvimento de aplicações backend
   - **Configuração Inicial do Projeto Spring Boot:**
     - Criação e configuração de um projeto Spring Boot usando Spring Initializr

#### Módulo 2: Implementação do Backend com Spring

5. **Aula 5: Padrão MVC e Configuração do Spring Boot**
   - **Conceito de MVC:**
     - Explicação do padrão MVC (Model, View, Controller)
   - **Configuração do Spring Boot:**
     - Estrutura do projeto Spring Boot
     - Configuração de dependências e arquivos de configuração

6. **Aula 6: Modelagem das Entidades - Evento, Ingresso, e Usuário**
   - **Definição das Entidades:**
     - Modelagem das entidades `Evento`, `Ingresso`, e `Usuário`
   - **Configuração das Entidades JPA:**
     - Anotações JPA e relacionamentos entre entidades

7. **Aula 7: Implementando Repositórios para CRUD**
   - **Criação dos Repositórios:**
     - Implementação de interfaces de repositório para `Evento`, `Ingresso`, e `Usuário`
   - **Operações CRUD Básicas:**
     - Métodos para criar, ler, atualizar e excluir registros

8. **Aula 8: Criando Serviços para Lógica de Negócio**
   - **Desenvolvimento dos Serviços:**
     - Implementação dos serviços para `Evento`, `Ingresso`, e `Usuário`
   - **Lógica de Negócio e Regras:**
     - Implementação de regras e validações de negócios

9. **Aula 9: Implementando Controllers e Endpoints**
   - **Criação dos Controllers:**
     - Implementação dos controllers para `Evento`, `Ingresso`, e `Usuário`
   - **Definição dos Endpoints RESTful:**
     - Configuração dos endpoints de API para operações CRUD

#### Módulo 3: Segurança e Autenticação

10. **Aula 10: Introdução ao Spring Security**
    - **O que é o Spring Security:**
      - Conceitos básicos de segurança em aplicações
    - **Configuração Básica de Segurança:**
      - Configuração inicial do Spring Security

11. **Aula 11: Implementando Autenticação e Autorização**
    - **Autenticação de Usuários:**
      - Configuração de login e autenticação
    - **Controle de Acesso e Permissões:**
      - Implementação de roles e permissões de acesso

#### Módulo 4: Funcionalidades e Integração

12. **Aula 12: Implementação da Funcionalidade de Compra de Ingressos**
    - **Criação de Endpoints para Compra:**
      - Implementação dos endpoints para compra de ingressos
    - **Lógica de Compra e Gestão de Ingressos:**
      - Implementação da lógica de compra e gerenciamento de ingressos

13. **Aula 13: Gerenciamento de Eventos e Usuários**
    - **Gerenciamento de Eventos:**
      - Funcionalidades para atualização e exclusão de eventos
    - **Gerenciamento de Usuários:**
      - Funcionalidades para administração e gerenciamento de usuários

14. **Aula 14: Integração e Testes**
    - **Integração dos Componentes:**
      - Integração entre controllers, serviços, e repositórios
    - **Testes de Unidade e Integração:**
      - Implementação de testes usando Spring Boot Test

#### Módulo 5: Conclusão e Deploy

15. **Aula 15: Revisão do Projeto e Deploy**
    - **Revisão Geral do Sistema:**
      - Verificação das funcionalidades e integração
    - **Deploy da Aplicação:**
      - Opções básicas de deploy e considerações finais

### Projeto Final: API de Gerenciamento de Eventos e Venda de Ingressos

**Funcionalidades:**
- **CRUD de Eventos:**
  - Cadastrar, ler, atualizar e excluir eventos (nome, descrição, data, local)
- **CRUD de Ingressos:**
  - Cadastrar, ler, atualizar e excluir ingressos (nome do comprador)
- **CRUD de Usuários:**
  - Cadastrar, ler, atualizar e excluir usuários (para gerenciar eventos e comprar ingressos)
- **Compra de Ingressos:**
  - Funcionalidade para os usuários comprarem ingressos para eventos
- **Gerenciamento de Eventos e Ingressos:**
  - Funcionalidades para que organizadores de eventos possam gerenciar eventos e ingressos

**Tecnologias Utilizadas:**
- **Backend:** Java, Spring Boot
- **Banco de Dados:** JPA/Hibernate
- **Segurança:** Spring Security
- **Padrão de Projeto:** MVC
