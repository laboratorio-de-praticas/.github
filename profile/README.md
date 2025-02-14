# Projeto: Sistema de Votação para a Faculdade

## Descrição do Projeto
O projeto consiste no desenvolvimento de um sistema de votação para a faculdade, que permitirá:
- Votação **interna e segura** para escolha de representantes de turma.
- Votação **pública** (aberta ao externo) para eleger o melhor projeto das nossas feiras tecnológicas **FTX e HubTec**.

O sistema deve ser seguro, acessível e funcional tanto para usuários internos (alunos e professores) quanto para o público externo. Além disso, o sistema deve fornecer **dashboards e relatórios** detalhados para garantir transparência e permitir auditorias, caso necessário.

---

## Cronograma

### Kick-off e Planejamento Inicial
- **Data:** 17 de fevereiro (segunda-feira).
- **Objetivo:** Apresentar o projeto, alinhar expectativas, definir papéis e priorizar as user stories.

### Atualizações de Andamento
As atualizações ocorrerão nas seguintes sextas-feiras:

| **Data**       | **Foco da Atualização**                                                                 |
|-----------------|----------------------------------------------------------------------------------------|
| **21/fev**     | Definição final das equipes e início do desenvolvimento das primeiras user stories.    |
| **28/fev**     | Revisão do protótipo de UX e validação da autenticação segura (Back-End).              |
| **07/mar**     | Entrega parcial: sistema de autenticação funcional e telas de votação interna.         |
| **14/mar**     | Revisão da votação interna e início do desenvolvimento da votação pública.             |
| **21/mar**     | Testes de usabilidade e acessibilidade nas telas de votação.                          |
| **28/mar**     | Entrega parcial: votação pública funcional e painel de resultados em tempo real.       |
| **04/abr**     | Revisão da segurança (criptografia, logs, integridade dos dados).                      |
| **11/abr**     | Testes finais e correção de bugs.                                                     |
| **25/abr**     | Preparação para a entrega final: documentação e ajustes finais.                       |

### Entregas Parciais
- **07/mar:**  
  - Sistema de autenticação seguro (Back-End).  
  - Protótipo de telas de votação interna (UX/Front).  

- **28/mar:**  
  - Votação pública funcional (Front-End/Back-End).  
  - Painel de resultados em tempo real (Back-End/DevOps).  

### Entrega Final
- **Data:** 5 de maio.
- **Objetivo:** Entregar o sistema completo, com todas as funcionalidades implementadas e testadas.

---

## Produtos e Funcionalidades

### 1. CMS (Content Management System)
**Descrição:**  
O CMS será o sistema de gerenciamento de conteúdo do projeto, permitindo que administradores cadastrem e gerenciem informações sobre candidatos (representantes de turma) e projetos das feiras FTX e HubTec.  

**Funcionalidades Principais:**  
- Cadastro de candidatos (representantes de turma) com fotos, descrições e informações relevantes.  
- Cadastro de projetos das feiras FTX e HubTec, incluindo título, descrição, equipe responsável e fotos.  
- Edição e exclusão de conteúdos cadastrados.  
- Interface amigável para administradores, com validação de dados e prevenção de erros.  
- Integração com o módulo de **Vitrine** para exibição dos projetos ao público.  

---

### 2. Dash e Reports (Dashboards e Relatórios)
**Descrição:**  
Este produto será responsável por fornecer transparência ao processo de votação, com dashboards em tempo real e relatórios detalhados para auditoria.  

**Funcionalidades Principais:**  
- Painel de resultados em tempo real, mostrando a distribuição de votos por candidato/projeto.  
- Gráficos interativos (ex.: barras, pizza) para visualização dos dados.  
- Relatórios detalhados com logs de atividades (quem votou, quando e em quem).  
- Exportação de relatórios em formatos como PDF e CSV.  
- Filtros para visualização de dados por período, turma ou feira (FTX/HubTec).  

---

### 3. Votação
**Descrição:**  
O núcleo do sistema, onde os usuários (alunos, professores e público externo) poderão votar de forma segura e anônima.  

**Funcionalidades Principais:**  
- Votação interna para escolha de representantes de turma, com autenticação segura.  
- Votação pública para eleger o melhor projeto das feiras FTX e HubTec, sem necessidade de login.  
- Interface simples e intuitiva, com confirmação visual do voto registrado.  
- Garantia de anonimato e integridade dos votos.  
- Limitação de um voto por usuário/dispositivo (controle por IP ou autenticação).  

---

### 4. Vitrine
**Descrição:**  
A vitrine será a interface pública do sistema, onde os projetos das feiras FTX e HubTec serão exibidos para o público votante.  

**Funcionalidades Principais:**  
- Exibição dos projetos cadastrados no CMS, com fotos, descrições e detalhes.  
- Filtros para busca de projetos por categoria, turma ou feira (FTX/HubTec).  
- Design responsivo, funcionando bem em dispositivos móveis e desktop.  
- Integração com o módulo de **Votação** para permitir que os usuários votem diretamente na vitrine.  
- Links para compartilhamento nas redes sociais, aumentando a visibilidade dos projetos.  

---

### 5. Autenticação e Segurança
**Descrição:**  
Este produto garantirá a segurança do sistema, protegendo dados sensíveis e garantindo que apenas usuários autorizados possam acessar funcionalidades específicas.  

**Funcionalidades Principais:**  
- Sistema de autenticação seguro, com login e senha (e opção de autenticação de dois fatores).  
- Criptografia de votos e dados sensíveis durante a transmissão e armazenamento.  
- Geração de logs de atividades para auditoria (ex.: tentativas de acesso, votos registrados).  
- Prevenção contra ataques comuns, como SQL injection e DDoS.  
- Validação de IP para limitar votos públicos a um por dispositivo.  

---

### 6. Integração e APIs
**Descrição:**  
Este produto cuidará da integração entre os diferentes módulos do sistema e com serviços externos, garantindo que tudo funcione de forma coesa e eficiente.  

**Funcionalidades Principais:**  
- Desenvolvimento de APIs para comunicação entre front-end e back-end.  
- Integração com serviços de autenticação externos (ex.: Google, Facebook).  
- Webhooks para notificações em tempo real (ex.: alertas de novos votos).  
- Documentação clara das APIs para facilitar a manutenção e futuras integrações.  

---

## Equipes e Responsabilidades
- **UX:** Prototipagem e design das interfaces.  
- **Front-End:** Desenvolvimento das telas de votação e painel de resultados.  
- **Back-End:** Lógica do sistema, autenticação e segurança.  
- **DevOps:** Configuração de servidores, monitoramento e CI/CD.  
- **Analytics:** Desenvolvimento de dashboards e relatórios (integração com Back-End).  

---

## Ferramentas Utilizadas
- **Gestão de Projeto:** Trello, Jira ou Notion.  
- **Desenvolvimento:** GitHub (versionamento), Docker (conteinerização).  
- **Dashboards:** Ferramentas como Power BI, Tableau ou bibliotecas como Chart.js/D3.js.  
- **Testes:** Ferramentas de teste de usabilidade e segurança.  

---

## Como Contribuir
1. Clone o repositório:  
   ```bash
   git clone https://github.com/seu-usuario/sistema-votacao.git
