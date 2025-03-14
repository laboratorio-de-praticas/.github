# Projeto: Sistema de Votação para a Faculdade

## Descrição do Projeto
O projeto consiste no desenvolvimento de um sistema de votação para a faculdade, que permitirá:
- Votação **interna e segura** para escolha de representantes de turma.
- Votação **pública** (aberta ao externo) para eleger o melhor projeto das nossas feiras tecnológicas **FTX e HubTec**.

O sistema deve ser seguro, acessível e funcional tanto para usuários internos (alunos e professores) quanto para o público externo. Além disso, o sistema deve fornecer **dashboards e relatórios** detalhados para garantir transparência e permitir auditorias, caso necessário.

---

## Cronograma

<details>
<summary><strong>Kick-off e Planejamento Inicial</strong></summary>

- **Data:** 17 de fevereiro (segunda-feira).
- **Objetivo:** Apresentar o projeto, alinhar expectativas, definir papéis e priorizar as user stories.
</details>

<details>
<summary><strong>Atualizações de Andamento</strong></summary>

As atualizações ocorrerão nas seguintes sextas-feiras:

| **Status**  | **Data**       | **Entregas**   | **Foco da Atualização**                                                         |
|-------------|----------------| ---------------|---------------------------------------------------------------------------------|
|     ✅      | **25/fev**     |        -       | Início do Projeto.                                                              |
|     ✅      | **28/fev**     | Entrega 1      | Definição final da user stories.                                                |
|     ⚙️      | **07/mar**     | Entrega 2      | Definição final das equipes e definição das stacks do projeto.                  |
|     ⚙️      | **14/mar**     | Entrega 3      | Revisão do protótipo de UX e validação da autenticação segura (Back-End).       |
|     ⚙️      | **21/mar**     | Entrega 4      | Entrega parcial: sistema de autenticação funcional e telas de votação interna.  |
|     ⚙️      | **28/mar**     | Entrega 5      | Revisão da votação interna e início do desenvolvimento da votação pública.      |
|     ⚙️      | **04/abr**     | Entrega 6      | Testes de usabilidade e acessibilidade nas telas de votação.                    |
|     ⚙️      | **11/abr**     | Entrega 7      | Entrega parcial: votação pública funcional e painel de resultados em tempo real.|
|     ⚙️      | **25/abr**     | Entrega 8      | Revisão da segurança (criptografia, logs, integridade dos dados).               |
</details>

<details>
<summary><strong>Entregas Parciais</strong></summary>

- **07/mar:**  
  - Sistema de autenticação seguro (Back-End).  
  - Protótipo de telas de votação interna (UX/Front).  

- **28/mar:**  
  - Votação pública funcional (Front-End/Back-End).  
  - Painel de resultados em tempo real (Back-End/DevOps).  
</details>

<details>
<summary><strong>Entrega Final</strong></summary>

- **Data:** 5 de maio.
- **Objetivo:** Entregar o sistema completo, com todas as funcionalidades implementadas e testadas.
</details>

---

## Produtos e Funcionalidades

<details>
<summary><strong>1. CMS (Content Management System)</strong></summary>

**Descrição:**  
O CMS será o sistema de gerenciamento de conteúdo do projeto, permitindo que administradores cadastrem e gerenciem informações sobre candidatos (representantes de turma) e projetos das feiras FTX e HubTec.  

**Funcionalidades Principais:**  
- Cadastro de candidatos (representantes de turma) com fotos, descrições e informações relevantes.  
- Cadastro de projetos das feiras FTX e HubTec, incluindo título, descrição, equipe responsável e fotos.  
- Edição e exclusão de conteúdos cadastrados.  
- Interface amigável para administradores, com validação de dados e prevenção de erros.  
- Integração com o módulo de **Vitrine** para exibição dos projetos ao público.

![Organograma - Equipe CMS - 2025_1](https://github.com/user-attachments/assets/3fa4255c-fdc9-42a1-a064-e371cb7c11e8)

</details>

<details>
<summary><strong>2. Dash e Reports (Dashboards e Relatórios)</strong></summary>

**Descrição:**  
Este produto será responsável por fornecer transparência ao processo de votação, com dashboards em tempo real e relatórios detalhados para auditoria.  

**Funcionalidades Principais:**  
- Painel de resultados em tempo real, mostrando a distribuição de votos por candidato/projeto.  
- Gráficos interativos (ex.: barras, pizza) para visualização dos dados.  
- Relatórios detalhados com logs de atividades (quem votou, quando e em quem).  
- Exportação de relatórios em formatos como PDF e CSV.  
- Filtros para visualização de dados por período, turma ou feira (FTX/HubTec).


![Organograma - Equipe Dash - 2025_1](https://private-user-images.githubusercontent.com/99757123/421576930-cafee9f7-1c94-4dcf-ad77-f1de6c15e0ed.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDE3MjgxMzAsIm5iZiI6MTc0MTcyNzgzMCwicGF0aCI6Ii85OTc1NzEyMy80MjE1NzY5MzAtY2FmZWU5ZjctMWM5NC00ZGNmLWFkNzctZjFkZTZjMTVlMGVkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTAzMTElMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwMzExVDIxMTcxMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTJhYzcyYzk0MDE1MDFlNGY3NjM3ZjBkYjhhYzY5MWJiZjM1OGEyMGEwZjE3YWI3YzMyMGYxNGMyZjk3OTEyMTEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.YtG0EHjMhiTZXEEOPxIMCSpZuO4ewbgDbazC_rDsiAE)

</details>

<details>
<summary><strong>3. Votação</strong></summary>

**Descrição:**  
O núcleo do sistema, onde os usuários (alunos, professores e público externo) poderão votar de forma segura e anônima.  

**Funcionalidades Principais:**  
- Votação interna para escolha de representantes de turma, com autenticação segura.  
- Votação pública para eleger o melhor projeto das feiras FTX e HubTec, sem necessidade de login.  
- Interface simples e intuitiva, com confirmação visual do voto registrado.  
- Garantia de anonimato e integridade dos votos.  
- Limitação de um voto por usuário/dispositivo (controle por IP ou autenticação).  

![ornograma-votacao](https://github.com/user-attachments/assets/3baf0fd8-7ec2-4423-b867-068c02769796)
</details>

<details>
<summary><strong>4. Vitrine</strong></summary>

**Descrição:**  
A vitrine será a interface pública do sistema, onde os projetos das feiras FTX e HubTec serão exibidos para o público votante.  

**Funcionalidades Principais:**  
- Exibição dos projetos cadastrados no CMS, com fotos, descrições e detalhes.  
- Filtros para busca de projetos por categoria, turma ou feira (FTX/HubTec).  
- Design responsivo, funcionando bem em dispositivos móveis e desktop.  
- Integração com o módulo de **Votação** para permitir que os usuários votem diretamente na vitrine.  
- Links para compartilhamento nas redes sociais, aumentando a visibilidade dos projetos.

![Organograma - Equipe Vitrine - 2025_1](https://github.com/user-attachments/assets/76df20ec-8717-4fba-8505-fcc229e0980b)


</details>

<details>
<summary><strong>5. Autenticação e Segurança</strong></summary>

**Descrição:**  
Este produto garantirá a segurança do sistema, protegendo dados sensíveis e garantindo que apenas usuários autorizados possam acessar funcionalidades específicas.  

**Funcionalidades Principais:**  
- Sistema de autenticação seguro, com login e senha (e opção de autenticação de dois fatores).  
- Criptografia de votos e dados sensíveis durante a transmissão e armazenamento.  
- Geração de logs de atividades para auditoria (ex.: tentativas de acesso, votos registrados).  
- Prevenção contra ataques comuns, como SQL injection e DDoS.  
- Validação de IP para limitar votos públicos a um por dispositivo.
  
![Organograma_Tribo_Integração](https://github.com/user-attachments/assets/8659191d-cf45-4f39-aa7c-54f528e1ae12)

</details>

<details>
<summary><strong>6. Integração e APIs</strong></summary>

**Descrição:**  
Este produto cuidará da integração entre os diferentes módulos do sistema e com serviços externos, garantindo que tudo funcione de forma coesa e eficiente.  

**Funcionalidades Principais:**  
- Desenvolvimento de APIs para comunicação entre front-end e back-end.  
- Integração com serviços de autenticação externos (ex.: Google, Facebook).  
- Webhooks para notificações em tempo real (ex.: alertas de novos votos).  
- Documentação clara das APIs para facilitar a manutenção e futuras integrações.  
</details>

![Organograma_Tribo_Integração drawio__1__2_](https://github.com/user-attachments/assets/84bbff36-b0db-4bc1-8629-8fbbd4b84d5c)


---

## Equipes e Responsabilidades

<details>
<summary><strong>Detalhes das Equipes</strong></summary>

- **UX:** Prototipagem e design das interfaces.  
- **Front-End:** Desenvolvimento das telas de votação e painel de resultados.  
- **Back-End:** Lógica do sistema, autenticação e segurança.  
- **DevOps:** Configuração de servidores, monitoramento e CI/CD.  
- **Analytics:** Desenvolvimento de dashboards e relatórios (integração com Back-End).  
</details>

---

## Ferramentas Utilizadas

<details>
<summary><strong>Lista de Ferramentas</strong></summary>

- **Gestão de Projeto:** GitHub (Projects).  
- **Desenvolvimento:** GitHub (versionamento), Docker (conteinerização).  
- **Testes:** Ferramentas de teste de usabilidade e segurança.  
</details>

---
