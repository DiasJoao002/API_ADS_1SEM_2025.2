##########


# Product Backlog - Plataforma de Treinamento Ágil

# Documentação do Projeto

<p align="center">
      <img src="https://i.imgur.com/your-logo-image-url.png" alt="logo do projeto" width="200">
      <h2 align="center">Plataforma de Treinamento Ágil</h2>
</p>

<p align="center">
  | <a href ="#desafio"> Desafio</a>  |
  <a href ="#us"> User Stories</a>  |
  <a href ="#detalhamento-us"> Detalhamento das User Stories</a>  |
  <a href ="#dor">DoR</a>  |
  <a href ="#dod">DoD</a>  |
</p>

> Status do Backlog: Em Refinamento ⚙️

## 🏅 Desafio <a id="desafio"></a>

O desafio consiste em desenvolver uma plataforma de treinamento online sobre metodologias ágeis e Scrum. O objetivo é criar uma experiência de aprendizado interativa para profissionais em treinamento, onde eles possam acessar conteúdos organizados em módulos, realizar exercícios com feedback imediato e analisar casos práticos. A plataforma visa aprimorar a compreensão teórica e prática dos usuários sobre o desenvolvimento de software ágil.

## 📋 Tabela de User Stories <a id="us"></a>

| Rank | Prioridade | User Story | Estimativa | Sprint |
| :--: | :--------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----: | :----: |
| 1 | Alta | [Como profissional em treinamento, quero acessar a plataforma e consultar um resumo sucinto acerca da metodologia para obter uma prévia do conteúdo.](#us1) | A Definir | 1 |
| 2 | Alta | [Como profissional em treinamento, quero acessar os conteúdos da plataforma organizados em módulos para aprimorar a compreensão da temática.](#us2) | A Definir | |
| 3 | Alta | [Como profissional em treinamento, quero acompanhar o progresso do curso para indicar minha posição atual.](#us3) | A Definir | |
| 4 | Alta | [Como profissional em treinamento, quero visualizar em um módulo específico as ferramentas utilizadas no dia a dia para compreender a rotina.](#us4) | A Definir | |
| 5 | Média | [Como profissional em treinamento, quero fazer exercícios para compreender os conceitos expostos nos módulos e ao concluir, evidenciar e explicar os erros.](#us5) | A Definir | |
| 6 | Média | [Como profissional em treinamento, quero analisar exemplos práticos da implementação da metodologia para mostrar como funciona na prática.](#us6) | A Definir | |
| 7 | Média | [Como profissional em treinamento, quero receber orientações sobre os princípios da metodologia para saber como proceder durante o processo de evolução.](#us7) | A Definir | |
| 8 | Média | [Como profissional em treinamento, quero acessar o meu perfil do curso para consultar dados significativos, como o avanço do curso.](#us8) | A Definir | |
| 9 | Baixa | [Como profissional em treinamento, quero interagir com um chatbot para esclarecer questionamentos e fornecer orientações sobre o curso.](#us9) | A Definir | |
| 10 | Baixa | [Como profissional em treinamento, quero receber sugestões de papéis que se alinham ao meu perfil profissional para aprimoramento.](#us10) | A Definir | |
| 11 | Baixa | [Como profissional em treinamento, quero receber uma certificação referente ao curso finalizado para ter uma confirmação oficial.](#us11) | A Definir | |

## 🔍 Detalhamento das User Stories <a id="detalhamento-us"></a>

---

### <a id="us1"></a> 1. Introdução inicial: exibir na tela inicial uma síntese das metodologias
**Como:** profissional em treinamento.
**Quero:** acessar a plataforma e consultar um resumo sucinto acerca da metodologia.
**Para:** obter uma prévia do conteúdo a ser abordado ao longo do curso.

**Critérios de Aceitação:**
* A página inicial deve exibir um resumo conciso sobre metodologias ágeis e Scrum.
* O resumo deve ser visualmente atraente e fácil de ler.
* Deve haver um botão ou link para iniciar o curso principal.
* O conteúdo precisa ser revisado e aprovado pelo PO.

**Checklist de Refinamento do Backlog (DoR):**
* **Sobre User Stories:**
    * [ ] Tem título claro, descrição bem definida e objetivo compreendido: Título e descrição foram detalhados. A equipe e o PO validaram que o objetivo é exibir um resumo na tela inicial.
    * [ ] Tem critérios de aceitação escritos: Sim. Definimos os critérios: exibir resumo conciso, ser visualmente atraente e ter botão para iniciar o curso.
    * [ ] Tem regras de negócio claras: A regra é que o conteúdo deve ser revisado e aprovado pelo Product Owner.
    * [ ] Sem dependências bloqueadoras: Deve-se verificar se há necessidade de outros componentes, como o layout da página principal, antes de iniciar.
    * [ ] Compreensão validada com o time: A equipe de desenvolvimento confirmou que entendeu o escopo.
* **Sobre artefatos correlatos às User Stories:**
    * [ ] Design/documentação disponível: O design da tela inicial e o layout do resumo devem estar prontos.
    * [ ] Estratégia de testes definida: A pessoa responsável pelos testes deve planejar como validar a exibição e o funcionamento do botão.

---

### <a id="us2"></a> 2. Conteúdo da plataforma distribuído em módulos
**Como:** profissional em treinamento.
**Quero:** acessar os conteúdos da plataforma organizados em módulos.
**Para:** aprimorar a compreensão da temática.

**Critérios de Aceitação:**
* A plataforma deve ter uma página dedicada aos módulos do curso.
* Cada módulo deve ter um título claro e uma breve descrição do conteúdo.
* Os módulos precisam ser apresentados em uma sequência lógica.
* Deve ser possível navegar entre os módulos.

**Checklist de Refinamento do Backlog (DoR):**
* **Sobre User Stories:**
    * [ ] Tem título claro, descrição bem definida e objetivo compreendido: Sim. O objetivo é organizar o conteúdo em módulos para facilitar o aprendizado.
    * [ ] Tem critérios de aceitação escritos: Sim. Os critérios incluem ter uma página de módulos, com títulos e descrições claras, e a possibilidade de navegação.
    * [ ] Tem regras de negócio claras: A regra é que a sequência dos módulos deve ser lógica e definida pelo PO.
    * [ ] Sem dependências bloqueadoras: Deve-se verificar se a estrutura do curso já foi definida e se o conteúdo de cada módulo está pronto.
    * [ ] Compreensão validada com o time: A equipe de desenvolvimento entendeu como a estrutura dos módulos será construída.
* **Sobre artefatos correlatos às User Stories:**
    * [ ] Design/documentação disponível: O design da página de módulos e a forma de exibição devem estar documentados.
    * [ ] Regras de negócio detalhadas: A sequência e a lista de módulos devem ser documentadas.
    * [ ] Estratégia de testes definida: A pessoa responsável pelos testes deve planejar como validar a navegação e a estrutura dos módulos.

---

### <a id="us3"></a> 3. Incluir uma visualização de progresso
**Como:** profissional em treinamento.
**Quero:** acompanhar o progresso do curso.
**Para:** indicar a posição atual dentro do curso.

**Critérios de Aceitação:**
* O progresso deve ser exibido em porcentagem (ex: 50%, 100%).
* A barra de progresso deve ser visível no painel do usuário.
* A porcentagem deve ser atualizada automaticamente conforme o usuário completa os módulos e atividades.

**Checklist de Refinamento do Backlog (DoR):**
* **Sobre User Stories:**
    * [ ] Tem título claro, descrição bem definida e objetivo compreendido: O objetivo de exibir o progresso em porcentagem para o usuário foi compreendido.
    * [ ] Tem critérios de aceitação escritos: Sim. Os critérios incluem que a barra de progresso deve ser visível e atualizada automaticamente.
    * [ ] Tem regras de negócio claras: A regra é que o cálculo da porcentagem deve ser preciso, baseado na conclusão de módulos e atividades.
    * [ ] Sem dependências bloqueadoras: Depende da existência de uma estrutura de curso e do controle de quais módulos foram concluídos.
    * [ ] Compreensão validada com o time: A equipe de desenvolvimento entendeu a lógica do cálculo do progresso.
* **Sobre artefatos correlatos às User Stories:**
    * [ ] Design/documentação disponível: O design da barra de progresso e sua localização na interface devem estar documentados.
    * [ ] Regras de negócio detalhadas: A fórmula para o cálculo do progresso (por exemplo, peso de cada módulo) deve ser documentada.
    * [ ] Modelo de dados disponível: O modelo para armazenar o histórico de progresso do usuário deve ser definido.
    * [ ] Estratégia de testes definida: A pessoa responsável pelos testes deve testar se o progresso é calculado e exibido corretamente após cada conclusão.

---

### <a id="us4"></a> 4. Indicação das ferramentas mais empregadas
**Como:** profissional em treinamento.
**Quero:** visualizar em um módulo específico as ferramentas utilizadas no dia a dia.
**Para:** compreender a rotina no decorrer do desenvolvimento de software.

**Critérios de Aceitação:**
* A plataforma deve incluir um módulo dedicado a "Ferramentas".
* O módulo deve listar as ferramentas mais comuns para cada atividade do Scrum (ex: Trello, Jira).
* Cada ferramenta listada deve ter uma breve descrição de sua função e exemplos de uso.
* Deve haver links para os sites oficiais das ferramentas.

**Checklist de Refinamento do Backlog (DoR):**
* **Sobre User Stories:**
    * [ ] Tem título claro, descrição bem definida e objetivo compreendido: O objetivo de listar as ferramentas do dia a dia foi compreendido.
    * [ ] Tem critérios de aceitação escritos: Sim. Os critérios incluem a criação de um módulo específico com a descrição, exemplos de uso e links das ferramentas.
    * [ ] Tem regras de negócio claras: A lista de ferramentas a ser incluída deve ser definida e aprovada pelo Scrum Master.
    * [ ] Sem dependências bloqueadoras: O conteúdo sobre as ferramentas deve estar pronto.
    * [ ] Compreensão validada com o time: A equipe de desenvolvimento entendeu como o módulo será construído.
* **Sobre artefatos correlatos às User Stories:**
    * [ ] Design/documentação disponível: O design da página do módulo de ferramentas e a apresentação de cada ferramenta devem estar prontos.
    * [ ] Regras de negócio detalhadas: O conteúdo de texto para cada ferramenta deve ser documentado.
    * [ ] Estratégia de testes definida: A pessoa responsável pelos testes deve testar a navegação e a exibição correta das informações das ferramentas.

---

### <a id="us5"></a> 5. Incluir perguntas de revisão
**Como:** profissional em treinamento.
**Quero:** fazer exercícios.
**Para:** compreender os conceitos expostos nos módulos e ao concluir cada questionário, evidenciar os erros e explicá-los para um retorno imediato e eficaz.

**Critérios de Aceitação:**
* Ao final de cada módulo, o usuário deve ter acesso a um questionário de revisão.
* O questionário deve incluir diferentes tipos de perguntas (múltipla escolha, verdadeiro ou falso, etc.).
* Ao responder, o sistema deve indicar se a resposta está correta ou errada.
* Para cada resposta incorreta, o sistema deve fornecer uma explicação clara do erro.
* O usuário deve poder refazer o questionário.

**Checklist de Refinamento do Backlog (DoR):**
* **Sobre User Stories:**
    * [ ] Tem título claro, descrição bem definida e objetivo compreendido: O objetivo é aprimorar o aprendizado com exercícios e feedback imediato.
    * [ ] Tem critérios de aceitação escritos: Sim. Os critérios incluem ter questionário no final dos módulos, diferentes tipos de perguntas, e feedback detalhado para cada erro.
    * [ ] Tem regras de negócio claras: As regras de pontuação e as explicações dos erros devem ser definidas pelo time.
    * [ ] Sem dependências bloqueadoras: Depende da conclusão do módulo de conteúdo ao qual os exercícios se referem.
    * [ ] Compreensão validada com o time: A equipe de desenvolvimento compreendeu como construir a funcionalidade de questionário e feedback.
* **Sobre artefatos correlatos às User Stories:**
    * [ ] Design/documentação disponível: O design da interface do questionário e do feedback devem ser elaborados.
    * [ ] Regras de negócio detalhadas: As perguntas e respostas de cada questionário, e as explicações dos erros, devem ser documentadas.
    * [ ] Modelo de dados disponível: O modelo para armazenar as perguntas, respostas e o histórico do usuário deve ser definido.
    * [ ] Estratégia de testes definida: A pessoa responsável pelos testes deve testar a lógica do questionário, o feedback, a pontuação e a capacidade de refazer o teste.

---

### <a id="us6"></a> 6. Análise de casos práticos
**Como:** profissional em treinamento.
**Quero:** analisar exemplos práticos da implementação da metodologia.
**Para:** mostrar como funciona na prática.

**Critérios de Aceitação:**
* Deve haver uma seção de "Casos Práticos" dentro do curso.
* Cada caso prático deve incluir uma descrição detalhada da situação.
* Deve-se apresentar como as metodologias ágeis foram aplicadas para resolver o problema.
* O conteúdo pode ser em formato de texto, vídeo ou infográfico.

**Checklist de Refinamento do Backlog (DoR):**
* **Sobre User Stories:**
    * [ ] Tem título claro, descrição bem definida e objetivo compreendido: O objetivo é fornecer exemplos práticos da aplicação da metodologia, e a equipe entendeu isso.
    * [ ] Tem critérios de aceitação escritos: Sim. Os critérios incluem a criação de uma seção dedicada e a apresentação detalhada de cada caso.
    * [ ] Tem regras de negócio claras: A regra é que os casos práticos devem ser aprovados pelo Product Owner e ser relevantes para o público-alvo.
    * [ ] Sem dependências bloqueadoras: O conteúdo dos casos práticos deve estar pronto e validado.
    * [ ] Compreensão validada com o time: A equipe de desenvolvimento entendeu como a seção será construída.
* **Sobre artefatos correlatos às User Stories:**
    * [ ] Design/documentação disponível: O design da seção de casos práticos e o formato de apresentação devem estar prontos.
    * [ ] Regras de negócio detalhadas: O texto e os detalhes dos casos práticos devem estar documentados.
    * [ ] Estratégia de testes definida: A pessoa responsável pelos testes deve testar a navegação e a exibição do conteúdo de cada caso.

---

### <a id="us7"></a> 7. Incluir conteúdo de orientações práticas de Skills
**Como:** profissional em treinamento.
**Quero:** receber orientações sobre os princípios da metodologia.
**Para:** orientação sobre como proceder durante o processo de evolução.

**Critérios de Aceitação:**
* O curso deve ter uma seção focada em "Habilidades e Práticas".
* O conteúdo deve incluir dicas sobre comunicação eficaz, colaboração em equipe e resolução de problemas, todos no contexto ágil.
* As orientações devem ser apresentadas de forma prática e acionável.
* O conteúdo deve ser revisado e aprovado pelo PO.

**Checklist de Refinamento do Backlog (DoR):**
* **Sobre User Stories:**
    * [ ] Tem título claro, descrição bem definida e objetivo compreendido: O objetivo é fornecer orientações práticas sobre os princípios da metodologia, e a equipe de desenvolvimento entendeu isso.
    * [ ] Tem critérios de aceitação escritos: Sim. Os critérios incluem uma seção dedicada a habilidades, com dicas práticas e conteúdo revisado e aprovado pelo PO.
    * [ ] Tem regras de negócio claras: A regra é que o conteúdo deve ser focado em aspectos práticos como comunicação, colaboração e resolução de problemas, no contexto ágil.
    * [ ] Sem dependências bloqueadoras: O conteúdo das orientações deve estar pronto para ser implementado.
    * [ ] Compreensão validada com o time: A equipe de desenvolvimento entendeu o escopo e o formato em que o conteúdo será apresentado.
* **Sobre artefatos correlatos às User Stories:**
    * [ ] Design/documentação disponível: O design da seção de habilidades deve estar pronto.
    * [ ] Regras de negócio detalhadas: O conteúdo de texto e exemplos para cada habilidade deve ser documentado.
    * [ ] Estratégia de testes definida: A pessoa responsável pelos testes deve planejar como testar a exibição e a organização do conteúdo.

---

### <a id="us8"></a> 8. Perfil de acesso do usuário
**Como:** profissional em treinamento.
**Quero:** acessar o meu perfil do curso.
**Para:** consultar dados significativos, como, por exemplo, o avanço do curso.

**Critérios de Aceitação:**
* A plataforma deve ter uma página de perfil do usuário.
* O perfil deve exibir o nome completo e o e-mail do usuário.
* Deve-se incluir um resumo do progresso do curso, como a porcentagem de conclusão.
* O perfil deve listar os módulos já concluídos.
* A página de perfil deve ser facilmente acessível a partir do menu principal da plataforma.
* O usuário deve conseguir editar informações básicas do perfil, como foto e nome de exibição.

**Checklist de Refinamento do Backlog (DoR):**
* **Sobre User Stories:**
    * [ ] Tem título claro, descrição bem definida e objetivo compreendido: O objetivo de permitir ao usuário acessar e consultar o seu perfil foi compreendido pela equipe.
    * [ ] Tem critérios de aceitação escritos: Sim. Os critérios incluem exibir nome, e-mail, resumo do progresso do curso e uma lista de módulos concluídos.
    * [ ] Tem regras de negócio claras: A regra é que os dados exibidos no perfil devem ser precisos e refletir o progresso real do usuário.
    * [ ] Sem dependências bloqueadoras: A funcionalidade de "Visualização de Progresso" e o sistema de registro de conclusão de módulos já devem estar implementados.
    * [ ] Compreensão validada com o time: A equipe de desenvolvimento entendeu como o perfil será construído e como ele se conectará aos dados do usuário.
* **Sobre artefatos correlatos às User Stories:**
    * [ ] Design/documentação disponível: O design da página de perfil e a disposição dos elementos devem estar prontos.
    * [ ] Regras de negócio detalhadas: A forma como o avanço é exibido e quais dados são considerados "significativos" devem ser documentadas.
    * [ ] Modelo de dados disponível: O modelo para o banco de dados que armazena as informações do usuário deve ser definido.
    * [ ] Estratégia de testes definida: A pessoa responsável pelos testes deve testar a exibição correta dos dados do usuário e a atualização do progresso.

---

### <a id="us9"></a> 9. Assistentes Virtuais e Mascotes
**Como:** profissional em treinamento.
**Quero:** estabelecer uma interação com um personagem por meio do chatbot.
**Para:** esclarecer questionamentos e fornecer orientações relacionadas ao conteúdo do curso.

**Critérios de Aceitação:**
* O chatbot deve ser acessível a partir de qualquer página do curso.
* O assistente virtual deve ter um nome e um design de personagem.
* Ele precisa ser capaz de responder a perguntas frequentes sobre o conteúdo do curso.
* Caso não saiba a resposta, deve direcionar o usuário para a seção correta do material ou sugerir um contato com o suporte.
* A interação deve ser amigável e instrutiva.

**Checklist de Refinamento do Backlog (DoR):**
* **Sobre User Stories:**
    * [ ] Tem título claro, descrição bem definida e objetivo compreendido: O objetivo de ter um chatbot para responder a perguntas e fornecer orientações foi compreendido.
    * [ ] Tem critérios de aceitação escritos: Sim. Os critérios incluem que o chatbot deve ser acessível, ter um personagem e ser capaz de responder a perguntas frequentes.
    * [ ] Tem regras de negócio claras: A regra é que o chatbot deve redirecionar o usuário para o suporte caso não consiga responder a uma pergunta. O conteúdo das respostas deve ser validado pelo PO.
    * [ ] Sem dependências bloqueadoras: A base de dados de perguntas e respostas para o chatbot deve estar pronta.
    * [ ] Compreensão validada com o time: A equipe de desenvolvimento entendeu como a funcionalidade de chatbot será integrada à plataforma.
* **Sobre artefatos correlatos às User Stories:**
    * [ ] Design/documentação disponível: O design do mascote, a interface do chatbot e os fluxos de conversação devem ser documentados.
    * [ ] Regras de negócio detalhadas: A lista de perguntas e respostas frequentes deve ser documentada.
    * [ ] Modelo de dados disponível: O modelo para armazenar as interações do chatbot e o histórico de conversas deve ser definido.
    * [ ] Estratégia de testes definida: A pessoa responsável pelos testes deve testar o fluxo de conversação do chatbot e a precisão das respostas.

---

### <a id="us10"></a> 10. Customização e Sugestão de Papéis
**Como:** profissional em treinamento.
**Quero:** receber sugestões acerca de quais papéis se alinham ao meu perfil profissional.
**Para:** aprimoramento profissional.

**Critérios de Aceitação:**
* O sistema deve coletar informações do perfil do usuário (ex: experiências anteriores, áreas de interesse).
* Com base nesses dados, o sistema deve sugerir papéis relevantes no contexto de metodologias ágeis (ex: Scrum Master, Product Owner, Desenvolvedor).
* Cada sugestão deve incluir uma breve descrição do papel e as habilidades necessárias.
* A sugestão deve ser apresentada em uma seção dedicada no perfil do usuário.

**Checklist de Refinamento do Backlog (DoR):**
* **Sobre User Stories:**
    * [ ] Tem título claro, descrição bem definida e objetivo compreendido: O objetivo de sugerir papéis profissionais com base no perfil do usuário foi compreendido.
    * [ ] Tem critérios de aceitação escritos: Sim. Os critérios incluem a coleta de informações do perfil, a sugestão de papéis com descrição e a apresentação em uma seção dedicada.
    * [ ] Tem regras de negócio claras: A regra para o algoritmo de sugestão de papéis e as descrições dos papéis devem ser definidas pelo PO.
    * [ ] Sem dependências bloqueadoras: O perfil do usuário deve estar funcional, e as informações necessárias para a sugestão de papéis devem ser coletadas.
    * [ ] Compreensão validada com o time: A equipe de desenvolvimento entendeu a lógica por trás da sugestão de papéis.
* **Sobre artefatos correlatos às User Stories:**
    * [ ] Design/documentação disponível: O design da seção de sugestão de papéis deve estar pronto.
    * [ ] Regras de negócio detalhadas: As regras do algoritmo de sugestão e as descrições dos papéis devem ser documentadas.
    * [ ] Modelo de dados disponível: O modelo para armazenar as informações de perfil e a lógica de sugestão deve ser definido.
    * [ ] Estratégia de testes definida: A pessoa responsável pelos testes deve testar se o algoritmo está funcionando corretamente e se as sugestões são relevantes.

---

### <a id="us11"></a> 11. Certificação
**Como:** profissional em treinamento.
**Quero:** receber uma certificação referente ao curso finalizado.
**Para:** ter uma confirmação oficial sobre o curso que foi feito.

**Critérios de Aceitação:**
* A certificação só pode ser emitida após o usuário ter completado 100% dos módulos do curso.
* O certificado deve conter o nome do curso e o nome completo do aluno.
* O certificado deve ter um design profissional e incluir um identificador único ou QR Code para validação.
* O usuário deve ter a opção de baixar o certificado em formato PDF.

**Checklist de Refinamento do Backlog (DoR):**
* **Sobre User Stories:**
    * [ ] Tem título claro, descrição bem definida e objetivo compreendido: O objetivo de emitir um certificado oficial após a conclusão do curso foi compreendido.
    * [ ] Tem critérios de aceitação escritos: Sim. Os critérios incluem que a certificação deve ser emitida somente após a conclusão do curso, e o documento deve ser profissional e ter a opção de download.
    * [ ] Tem regras de negócio claras: A regra é que o certificado só pode ser gerado se o usuário tiver completado 100% dos módulos. O conteúdo e o design do certificado devem ser aprovados pelo PO.
    * [ ] Sem dependências bloqueadoras: O sistema deve ter a funcionalidade de registrar a conclusão de 100% do curso.
    * [ ] Compreensão validada com o time: A equipe de desenvolvimento entendeu como o certificado será gerado.
* **Sobre artefatos correlatos às User Stories:**
    * [ ] Design/documentação disponível: O design do certificado e o seu formato (ex: PDF) devem ser documentados.
    * [ ] Regras de negócio detalhadas: As informações que devem constar no certificado (nome do curso, nome do aluno, identificador único) devem ser documentadas.
    * [ ] Estratégia de testes definida: A pessoa responsável pelos testes deve testar o processo de geração e download do certificado.

---

## 🏅 DoR - Definition of Ready <a id="dor"></a>

A *Definition of Ready* (Definição de Pronto) é um conjunto de critérios que uma User Story deve atender antes de ser considerada pronta para ser puxada para uma Sprint. Ela garante que a equipe tenha informações suficientes para começar a trabalhar sem grandes impedimentos.

|             Critério             | Descrição                                                                                         |
| :------------------------------: | ------------------------------------------------------------------------------------------------- |
|       Clareza na Descrição       | A User Story está escrita no formato “Como [persona], quero [ação] para que [objetivo]”.           |
| Critérios de Aceitação Definidos | A história possui critérios objetivos que indicam o que é necessário para considerá-la concluída. |
|           Independente           | A história pode ser implementada sem depender de outra tarefa da mesma Sprint.                    |
|    Compreensão Compartilhada     | Toda a equipe (incluindo PO e devs) compreende o propósito e o escopo da história.                 |
|            Estímável             | A história foi pontuada ou tem uma estimativa de esforço clara pela equipe de desenvolvimento.      |
|       Documentos de Apoio        | Se necessário, mockups, fluxos ou modelos de dados estão anexados ou referenciados.               |

## 🏅 DoD - Definition of Done <a id="dod"></a>

A *Definition of Done* (Definição de Concluído) é um checklist de atividades necessárias para que um incremento de produto seja considerado "concluído". Garante que o trabalho entregue tenha um padrão de qualidade consistente.

|                 Critério                 | Descrição                                                                            |
| :--------------------------------------: | ------------------------------------------------------------------------------------ |
|     Critérios de Aceitação atendidos     | Todos os critérios de aceitação da User Story foram atendidos e validados.            |
|        Testes manuais realizados         | A funcionalidade foi testada manualmente em diferentes cenários e dispositivos.      |
|             Código revisado              | O código foi revisado por pelo menos um outro membro da equipe de desenvolvimento (Code Review).|
|     Documentação interna atualizada      | A documentação técnica relevante (se houver) foi criada ou atualizada.               |
| Build/Testes automatizados bem-sucedidos | A funcionalidade passa em todos os testes automatizados (unitários, integração, etc.). |
|             Validação do PO              | O Product Owner validou a entrega com base nos critérios de aceitação definidos.      |
|            Pronto para deploy            | O incremento está integrado à branch principal e pronto para ser implantado em produção. |


########