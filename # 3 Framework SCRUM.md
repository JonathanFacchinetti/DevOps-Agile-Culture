# Framework SCRUM

O Scrum é um framework simples para gerenciar projetos complexos, através de uma dinâmica, papéis e cerimônias no decorrer de todo o ciclo. O Scrum foi concebido na década de 1990, e o termo foi inspirado em uma jogada de rúgbi em que 8 jogadores se reúnem para retirar os obstáculos à frente do jogador que correrá com a bola, utilizando-se do próprio corpo como principal armadura para livrar o companheiro do time, para que assim ele consiga avançar o máximo possível e marcar mais pontos. Essa analogia descreve a importância das equipes e seu trabalho em conjunto para resolver os mais variados problemas.

O Scrum não restringe sua aplicação apenas para a área de TI, ele pode ser aplicado em projetos diversos que possuem complexidade. A abordagem incremental e interativa é utilizada fortemente no Scrum, onde a cada determinado espaço de tempo, uma funcionalidade do produto que faz parte de um todo é entregue. Vamos aprender sobre os pilares do Scrum para compreender melhor suas características.

## Índice

1. [Pilares do Scrum](#pilares-do-scrum)
2. [Papéis Fundamentais](#papéis-fundamentais)
    - [Product Owner (PO)](#product-owner-po)
    - [Scrum Master (SM)](#scrum-master-sm)
    - [Time Scrum](#time-scrum)
3. [Valores do Scrum](#valores-do-scrum)
4. [Princípios do Scrum](#princípios-do-scrum)
5. [Dinâmicas, Cerimônias e Artefatos](#dinâmicas-cerimônias-e-artefatos)
    - [Product Backlog e User Stories](#1-product-backlog-e-user-stories)
    - [Sprints](#2-sprints)
    - [Sprint Planning](#3-sprint-planning)
        - [Fases de Planejamento](#fases-de-planejamento)
    - [Daily Scrum](#4-daily-scrum)
    - [Definition of Done (DoD)](#5-definition-of-done-dod)
    - [Sprint Review](#6-sprint-review)
    - [Sprint Retrospective](#7-sprint-retrospective)
6. [Resumo sobre Scrum](#resumo-sobre-scrum)
7. [Caso de Uso](#caso-de-uso)
8. [Kanban](#kanban)
    - [Quadro com Fluxo de Trabalho](#um-quadro-com-fluxo-de-trabalho)
    - [Sistema Empurrado vs. Sistema Puxado](#sistema-empurrado-vs-sistema-puxado)
    - [Princípios do Kanban](#princípios-do-kanban)
    - [Práticas do Kanban](#práticas-do-kanban)
    - [Elementos do Sistema Kanban](#elementos-do-sistema-kanban)
    - [Vantagens do Kanban em Relação ao Scrum](#vantagens-do-kanban-em-relação-ao-scrum)
9. [Conclusão](#conclusão)

## Pilares do Scrum

- **Transparência**: Todos possuem o conhecimento dos requisitos, processos e do andamento do projeto.
- **Inspeção**: Durante todo o tempo é inspecionado o que está sendo feito, através de reuniões diárias ou no momento de uma revisão.
- **Adaptação**: Conforme as mudanças vão acontecendo, tanto o processo quanto o produto podem sofrer adaptações, desde que preservados os valores e práticas ágeis.

![Pilares SCRUM](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/Imagens%20diversas/Pilares%20SCRUM.png)

## Papéis Fundamentais

Para a realização do Scrum, são necessários **3 papéis fundamentais**. Sem esses papéis, não temos o Scrum:

### Product Owner (PO)

- **Responsabilidades**:
    - Decidir quais recursos e funcionalidades o produto deve ter.
    - Definir a ordem de prioridade das funcionalidades.
    - Manter e comunicar uma visão clara do que o Time Scrum está trabalhando no produto.
    - Servir como ponto de intersecção entre a área de negócios e a área de desenvolvimento.
- **Importância**:
    - Autonomia para tomar decisões sobre o produto.
    - Evita a criação de um "PO Proxy", garantindo que o PO saiba exatamente o que deve ser feito.

![Product Owner](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/Imagens%20diversas/Product%20Owner.png)

### Scrum Master (SM)

- **Responsabilidades**:
    - Ajudar os envolvidos a entender a cultura ágil e os princípios do Scrum.
    - Facilitar a resolução de conflitos e remoção de impedimentos.
    - Proteger o time contra interferências externas.
    - Promover o desenvolvimento da equipe para que se torne independente.
- **Importância**:
    - Atua como líder do processo e facilitador.
    - Evita a confusão entre o papel de Scrum Master e o de chefe.

![Scrum Master](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/Imagens%20diversas/Scrum%20Master.png)

### Time Scrum

- **Composição**:
    - Equipe de desenvolvimento com diversos membros e habilidades necessárias.
- **Responsabilidades**:
    - Decidir como alcançar o objetivo do desenvolvimento.
    - Trabalhar de forma auto-organizada e multidisciplinar.
    - Manter o time entre 4 e 8 pessoas para garantir eficiência.
- **Importância**:
    - Promove a colaboração e a entrega contínua de valor.

![Time Scrum](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/Imagens%20diversas/Time%20Scrum.png)

## Valores do Scrum

Assim como no Manifesto Ágil, o Scrum também possui seus próprios valores, que dão personalidades aos papéis:

- **Foco**
    - Todos estão focados em um único objetivo.
    - Mantém o time concentrado em pequenas partes por vez, alinhadas com a priorização do Product Owner.
    - O Scrum Master facilita a remoção de impedimentos para manter o foco.

- **Coragem**
    - O time enfrenta desafios de forma correta e eficiente.
    - Aceita mudanças, corrige erros e aprende rapidamente com eles.

- **Comprometimento**
    - Cada papel possui seu comprometimento específico:
        - Time Scrum: Realizar o que foi acordado.
        - Scrum Master: "Girar a Roda" do framework Scrum junto ao time.
        - Product Owner: Priorizar as necessidades de negócio e gerenciar o produto.

- **Respeito**
    - Membros do time respeitam uns aos outros e suas diferenças.
    - Product Owner respeita as decisões técnicas do Time Scrum e vice-versa.

- **Abertura**
    - Equipe está aberta a feedbacks e a discutir situações.
    - Promove a visibilidade dos problemas e a clareza no trabalho realizado.

## Princípios do Scrum

Os princípios do Scrum complementam os valores e são fundamentais para o bom funcionamento do framework. Eles são:

- **Controle dos Processos Empíricos**
    - Decisões baseadas em observação e experimentação.
    - Utiliza os pilares da transparência, inspeção e adaptação ao longo dos ciclos.

- **Auto-organização**
    - Times são auto-organizáveis e possuem responsabilidade compartilhada.
    - Atuando ponta a ponta no desenvolvimento do produto, entregando maior valor de forma independente.

- **Colaboração**
    - Trabalho colaborativo promove criação de valor compartilhado.
    - Times trabalham juntos para alcançar melhores resultados.

- **Priorização Baseada em Valor**
    - Prioriza com base em valor, risco, incerteza e dependências.
    - Resulta em entregas que fornecem o maior valor de negócio no menor tempo possível.

- **Time-boxing**
    - Define períodos de tempo fixos para processos e atividades.
    - Garante uso eficiente do tempo, evitando esforços desperdiçados.

- **Desenvolvimento Iterativo**
    - Permite que os times aprendam e evoluam ao longo dos ciclos.
    - Promove refinamentos contínuos e entrega incremental.

## Dinâmicas, Cerimônias e Artefatos

No Scrum, tudo começa com a visão de um produto, onde o Product Owner descreve o que quer do produto e onde deseja chegar. A partir dessa visão macro, o Product Owner lista as funcionalidades necessárias, criando o artefato **Product Backlog**.

### 1. Product Backlog e User Stories

- **Product Backlog**: Lista priorizada das funcionalidades necessárias.
- **User Stories**: Definidas pelo Product Owner, descrevem de forma simples quem é o usuário, o que ele quer e qual é o objetivo.

### 2. Sprints

- **Sprints**: Períodos de tempo limitados (normalmente de 2 a 4 semanas) para desenvolver funcionalidades de valor tangível.
- **Objetivo**: Criar algo de valor para o cliente ou usuário.

### 3. Sprint Planning

- **Sprint Planning**: Cerimônia para definir o objetivo da Sprint e quais User Stories serão desenvolvidas.
- **Participantes**: Product Owner, Scrum Master e Time Scrum.
- **Atividades**:
    - Concordar sobre a capacidade e velocidade da equipe.
    - Utilizar **Planning Poker** para estimar o tamanho das atividades.

#### Fases de Planejamento

- **Planning Estratégico**: Define o que será feito.
- **Planning Tático**: Define como será feito.

### 4. Daily Scrum

- **Daily Scrum**: Reunião diária de alinhamento rápido.
- **Duração**: Máximo de 15 minutos.
- **Formato**: Stand-Up Meeting (em pé).
- **Perguntas Fundamentais**:
    1. O que eu fiz ontem que contribuiu para a meta do Sprint?
    2. O que eu farei hoje para contribuir para a meta do Sprint?
    3. Existe alguma circunstância que impeça a mim ou ao time de atingir a meta do Sprint?

### 5. Definition of Done (DoD)

- **Definition of Done (DoD)**: Acordo formal que define os passos mínimos para a conclusão de um item potencialmente entregável.
- **Objetivo**: Garantir clareza sobre o que significa uma tarefa estar concluída.

### 6. Sprint Review

- **Sprint Review**: Cerimônia para apresentar o que foi feito e adaptar o produto em desenvolvimento.
- **Objetivo**: Verificar e adaptar o produto conforme necessário.
- **Prática Recomendada**: Apresentações informais ao Product Owner durante o Sprint para possíveis adaptações.

### 7. Sprint Retrospective

- **Sprint Retrospective**: Cerimônia para verificar necessidades de adaptações e melhorias no processo de trabalho.
- **Objetivo**: Levantar pontos positivos e áreas de melhoria, focando nas causas raiz da Sprint que passou.

## Resumo sobre Scrum

No Scrum, o processo começa com a **visão de um produto**, onde o **Product Owner** descreve o que deseja do produto e onde quer chegar. A partir dessa visão, o Product Owner lista as funcionalidades necessárias, criando o artefato **Product Backlog**.

### 1. Product Backlog e User Stories

Com o backlog em mãos, o Product Owner prioriza as atividades com base no valor. Cada funcionalidade é definida como uma **User Story**, que descreve, de forma simples, quem é o usuário, o que ele deseja e qual é o objetivo.

### 2. Sprints

As **User Stories** do backlog são desenvolvidas de forma iterativa por meio de **Sprints**. Sprints são períodos de tempo limitados (normalmente de 2 a 4 semanas) com o objetivo de criar algo de valor tangível para o cliente ou usuário.

### 3. Sprint Planning

Antes de cada Sprint, realiza-se a cerimônia de **Sprint Planning** para definir o objetivo da Sprint e quais User Stories serão desenvolvidas. Durante o planejamento, o Product Owner, o Scrum Master e o Time Scrum concordam sobre a capacidade e velocidade da equipe. O **Planning Poker** pode ser utilizado para estimar o tamanho das atividades, onde os integrantes votam com cartas.

### Fases de Planejamento

Existem duas fases de planejamento:
- **Planning Estratégico**: Define o que será feito.
- **Planning Tático**: Define como será feito.

### 4. Daily Scrum

Com o Sprint definido, o desenvolvimento das atividades é iniciado. Diariamente, é realizada uma reunião de alinhamento rápido, chamada **Daily Scrum**, onde três perguntas devem ser respondidas:
1. O que eu fiz ontem que contribuiu para a meta do Sprint?
2. O que eu farei hoje para contribuir para a meta do Sprint?
3. Existe alguma circunstância que impeça a mim ou ao time de atingir a meta do Sprint?

O Daily deve durar no máximo 15 minutos e idealmente acontecer no mesmo horário. O Product Owner pode participar de forma opcional, e a prática de realizar o Daily em pé (Stand-Up Meeting) é recomendada para promover agilidade.

### 5. Definition of Done (DoD)

Durante o Sprint, para determinar se uma atividade pode ser considerada concluída, utiliza-se o conceito de **Definition of Done (DoD)**. Este é um acordo formal que define claramente quais são os passos mínimos para a conclusão de um item potencialmente entregável.

### 6. Sprint Review

Perto de finalizar o Sprint, realiza-se a cerimônia de **Sprint Review** para apresentar o que foi feito e adaptar o produto em desenvolvimento. É ideal que durante o Sprint, haja apresentações informais ao Product Owner para possíveis adaptações.

### 7. Sprint Retrospective

Por fim, a cerimônia de **Sprint Retrospective** é realizada. Enquanto o objetivo do Sprint Review é verificar necessidades de adaptações no produto, o Sprint Retrospective foca em melhorias no processo de trabalho. É importante levantar os pontos positivos e áreas de melhoria, sempre focando nas causas raiz da Sprint que passou.

## Caso de Uso

O framework Scrum é ideal para equipes que desejam adotar a cultura ágil e para projetos que possuem uma janela de entrega constante. Sua metodologia bem estruturada, que abrange todo o processo, oferece um direcionamento claro sobre o que deve ser feito. Além disso, à medida que a equipe amadurece, o Scrum permite adaptações para melhor atender às suas necessidades. O framework utiliza elementos visuais, como o quadro Kanban, para gerenciar as atividades, que será abordado posteriormente no método Kanban.

### Um Quadro com Fluxo de Trabalho

Para iniciar o estudo referente ao método Kanban, é necessário diferenciar a palavra **Kanban** com "K" maiúsculo e kanban com "k" minúsculo. O kanban refere-se à utilização com o fluxo de trabalho, com os respectivos cartões que representam as atividades, sua origem é japonesa e significa literalmente "cartão" ou "sinalização", enquanto o Kanban refere-se ao método de desenvolvimento ágil criado em 2005, influenciado pelo Sistema Toyota de Produção.

No modelo corporativo tradicional, a transição de mudanças geralmente ocorre de forma radical dentro de um determinado período de tempo. No entanto, como em qualquer mudança, existe um período de adaptação no qual podem ocorrer possíveis prejuízos até que a nova situação se estabilize e comece a gerar o retorno desejado. Dependendo do nível da mudança proposta, a organização pode não ter uma estrutura adequada para suportá-la e, por isso, optar por reverter a decisão ou, no pior cenário, até mesmo enfrentar a falência. Esse tipo de comportamento organizacional, em que uma mudança radical no status dentro de um período limitado impacta a capacidade da organização, é conhecido como **Kaikaku**.

Para trabalharmos mudanças de forma incremental, sem que o período de adaptação seja muito grande e diminuindo o risco da mudança, temos a abordagem de evolução **Kaizen**, que visa ciclos de iterações e melhorias contínuas referentes à mudança organizacional, com o objetivo de eliminar desperdícios e fazer "hoje melhor do que ontem, amanhã melhor do que hoje!"

Quando falamos sobre metodologias de desenvolvimento ágil, o modelo de **Evolução Kaizen** é altamente aderente e está profundamente enraizado na filosofia dessas metodologias. O método **Kanban** é um ótimo exemplo disso. Ele é composto por um fluxo de valor no qual as etapas de trabalho são mapeadas em um quadro Kanban. As atividades fluem da esquerda para a direita, e cada etapa adiciona uma melhoria de valor ao item. Quando o item chega ao final do quadro, ele estará concluído, entregando valor completo.


## Princípios do Kanban

- **Comece com o que você tem hoje.**
- **Concorde em propor mudanças incrementais e evolucionárias.**
- **Respeite o processo atual, papéis, responsabilidades e títulos.**
- **Encoraje atos de liderança em todos os níveis.**

## Práticas do Kanban

Para o sucesso da implementação do método Kanban, existem **6 práticas** essenciais:

1. **Visualizar o fluxo de trabalho**
    - Cria um modelo visual do fluxo de trabalho no quadro Kanban.
    - Facilita a identificação de problemas e bloqueios.

2. **Limitar o trabalho em progresso (WIP)**
    - Equilibra o ritmo da equipe.
    - Evita sistemas de empurrão e aumenta a eficiência.

3. **Gerenciar e medir o fluxo**
    - Coleta métricas para identificar problemas e oportunidades de otimização contínua.

4. **Tornar as políticas de processo explícitas**
    - Regras claras e compreendidas por todos os envolvidos.
    - Melhora a implementação e a adesão ao processo.

5. **Implementar ciclos de feedback**
    - Promove ciclos de feedback através de cerimônias específicas.
    - Permite adaptação e verificação de padrões de qualidade.

6. **Melhorar colaborativamente**
    - Utiliza o **Kaizen** para promover mudanças contínuas e incrementais.
    - Foco na melhoria constante do processo.

## Elementos do Sistema Kanban

### Colunas do Kanban

- Representam as fases de trabalho no quadro Kanban.
- Itens mais à direita indicam mais valor e tempo investidos.
- **Debate na comunidade ágil**:
    - Se um item pode ou não voltar para uma coluna anterior após identificação de erro.

### Raias

- Raias horizontais para destacar diferentes tipos de atividades.
- Exemplo: *fast-lane* ou *expedite* para atividades urgentes.

### Cartões

- Representam atividades de trabalho.
- Geralmente são post-its em quadros físicos.
- Anotações: atividades, responsáveis, impedimentos, etc.

### Limite de WIP

- Controla o fluxo de trabalho e evita sobrecargas.
- Ajusta a capacidade do time conforme necessário.
- **Teoria das filas**: Fluxo constante evita desperdício e sobrecarga.

### Políticas Explícitas

- Regras e fluxos de trabalho visíveis para todos.
- Exemplos:
    - Limites de WIP respeitados.
    - Apenas responsáveis podem mover atividades para "Pronto".

## Vantagens do Kanban em Relação ao Scrum

### Múltiplos Focos

- **Scrum**:
    - Requer criação de múltiplos times para diferentes focos (ex: manutenção e desenvolvimento).
- **Kanban**:
    - Permite que um único time gerencie múltiplos focos simultaneamente.

### Entregas Constantes

- **Scrum**:
    - Estrutura de *sprints* pode dificultar ciclos menores de entrega.
- **Kanban**:
    - Flexibilidade para entregas contínuas e mais frequentes.

### Mais Evolutivo

- **Scrum**:
    - Requer mudanças iniciais no processo.
    - Exige times pequenos.
- **Kanban**:
    - Inicia com o que se tem, sem mudanças drásticas.
    - Permite evoluções incrementais e adaptativas.

---

No fim, a escolha entre **Scrum** e **Kanban** depende das necessidades e particularidades de cada equipe e projeto. O Kanban pode ser mais adequado para times que precisam de flexibilidade e querem evoluir suas práticas de forma gradual, enquanto o Scrum pode ser preferível para equipes que se beneficiam de um framework mais estruturado.

## Conclusão

O método **Kanban** é recomendado para times que já conhecem a cultura ágil e precisam trabalhar em escopos de trabalho variados (manutenção, novas funcionalidades, operação). Muitos associam o Kanban a uma evolução do Scrum. Apesar de ser mais leve e menos prescritivo, o Kanban tem maiores chances de sucesso quando completado com as práticas do Scrum, como cerimônias, papéis e responsabilidades, desenvolvimento incremental do produto, trabalho em equipe, priorização de trabalho de acordo com maior valor para o cliente ou produto, entre outros. A junção do framework Scrum e do método Kanban está sendo denominada no mercado como **Scrumban**. Seja qual for a metodologia de desenvolvimento ágil que você for adotar, escolha aquela que mais se adapte ao seu projeto, produto, pessoas e organização.
