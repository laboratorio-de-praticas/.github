# Projeto: Sistema de Votação para a Faculdade

## Descrição do Projeto
O projeto consiste no desenvolvimento de um sistema de votação para a faculdade, que permitirá:
- Votação **interna e segura** para escolha de representantes de turma.
- Votação **pública** (aberta ao externo) para eleger o melhor projeto da feira de apresentações.

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

## User Stories

### 1. Autenticação Segura
- **Como** administrador do sistema,  
- **quero** que os usuários se autentiquem com login e senha (ou autenticação de dois fatores),  
- **para que** apenas pessoas autorizadas possam acessar a votação interna.  

### 2. Votação Interna (Representante de Turma)
- **Como** aluno,  
- **quero** votar no representante da minha turma de forma anônima e segura,  
- **para que** minha escolha seja confidencial e o resultado seja justo.  

### 3. Votação Pública (Melhor Projeto da Feira)
- **Como** membro do público externo,  
- **quero** votar no melhor projeto da feira de forma simples e acessível,  
- **para que** minha opinião seja considerada na premiação.  

### 4. Painel de Resultados em Tempo Real
- **Como** organizador da votação,  
- **quero** visualizar os resultados em tempo real,  
- **para que** eu possa acompanhar o progresso da votação e tomar decisões, se necessário.  

### 5. Acessibilidade e Usabilidade
- **Como** usuário com deficiência visual,  
- **quero** que o sistema seja acessível com leitores de tela e teclado navegável,  
- **para que** eu possa votar de forma independente.  

### 6. Segurança e Integridade dos Dados
- **Como** administrador do sistema,  
- **quero** que os votos sejam criptografados e armazenados com integridade,  
- **para que** o processo seja confiável e à prova de fraudes.  

### 7. Dashboards e Relatórios para Auditoria
- **Como** administrador do sistema,  
- **quero** gerar dashboards e relatórios detalhados sobre as votações,  
- **para que** haja transparência e seja possível realizar auditorias, se necessário.  

**Critérios de Aceitação:**  
- Os dashboards devem exibir métricas como:  
  - Número total de votos.  
  - Distribuição de votos por candidato/projeto.  
  - Horários de pico de votação.  
- Os relatórios devem incluir:  
  - Logs de atividades (quem votou, quando e em quem).  
  - Dados criptografados para garantir a privacidade dos votantes.  
  - Exportação em formatos como PDF e CSV.  

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
