# Métricas de Eficiência (Organizacional)

O trabalho na organização começa desde a hipótese de algo até o atingimento de um objetivo, e no meio do caminho dexistem diversas etapas com diferentes áreas da organização. As métricas de eficiência são o melhor caminho para se determinar se estamos trabalhando da melhor forma e identificar gargalos, solucionando-os em busca da melhoria continua.

## Índice
1. [Lead Time - Tempo de espera](#lead-time---tempo-de-espera)
2. [Cycle Time - Tempo do ciclo](#cycle-time---tempo-do-ciclo)
3. [Waiting Time e Touching Time](#waiting-time-e-touching-time)
4. [Flow Efficiency - Fluxo de eficiência](#flow-efficiency---fluxo-de-eficiência)
5. [Working in Progress (WIP) - Trabalho em progresso](#working-in-progress-wip---trabalho-em-progresso)
6. [Throughput - Vazão](#throughput---vazão)
7. [Cumulative Flow Diagram (CFD) - Diagrama de Fluxo Cumulativo](#cumulative-flow-diagram-cfd---diagrama-de-fluxo-cumulativo)
8. [Control Chart - Gráfico de Controle](#control-chart---gráfico-de-controle)
9. [Métricas de Eficácia (Negócio)](#métricas-de-eficácia-negócio)
   - 9.1 [ROI (Return on Investment)](#roi-return-on-investment)
   - 9.2 [NPS (Net Promoter Score)](#nps-net-promoter-score)
   - 9.3 [Churn](#churn)
10. [Métricas de Atmosfera (Cultural)](#métricas-de-atmosfera-cultural)
    - 10.1 [Turnover](#turnover)
    - 10.2 [Happiness Radar](#happiness-radar)
11. [Métricas de Qualidade (Técnica)](#métricas-de-qualidade-técnica)
    - 11.1 [Notificação de Problemas](#notificação-de-problemas)
    - 11.2 [Cobertura de Testes](#cobertura-de-testes)
12. [Métricas Tóxicas e de Vaidade](#métricas-tóxicas-e-de-vaidade)
    - 12.1 [Métricas Tóxicas](#métricas-tóxicas)
    - 12.2 [Métricas de Vaidade](#métricas-de-vaidade)
13. [Conclusão](#conclusão)

## Lead Time - Tempo de espera

Considerado como uma das métricas de eficiência mais importantes, o Lead Time (Tempo de espera) nos traz informações sobre o número de dias (tempo) entre o início e o fim do processo de entrega. Se o objetivo for construir uma ponte, por exemplo, o tempo de dias que decorre desde o início da ideia, passando pela construção até chegar a finalização da ponte é o nosso lead time. No mundo organizacional, o lead time está relacionado ao *time to market*, que é o tempo que um produto leva desde a sua concepção até que ele esteja totalmente disponível para venda ou consumo. Em geral, buscamos ter o menor lead time possível, para assim entregar e obter feedback o quanto antes. Existe uma discussão na comunidade sobre se o lead time se refere apenas ao tempo do trabalho do time de desenvolvimento; no quadro kanban, por exemplo, seria do backlog quando a história fosse criada até a história ser considerada concluída (done). Para não restar dúvidas, é importante definir com a organização o que ela considerada Lead Time

![Lead Time](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/M%C3%A9tricas%20de%20Efici%C3%AAncia/Lead%20Time.png)

## Cycle Time - Tempo do ciclo ou Local Lead Time - Tempo de espera local

O Lead Time olha para o tempo total do processo de entrega, e como normalmente busca-se diminuir esse tempo, é necessário identificar e analisar cada tempo específico de determinada etapa e, assim, realizar alguma ação, para isso utilizamos o CYCLE TIME (tempo do ciclo), também chamado de LOCAL LEAD TIME (tempo de espera local), que nos dá a informação entre o início e o fim de uma ou mais etapas do processo.

![Cycle Time](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/M%C3%A9tricas%20de%20Efici%C3%AAncia/Cycle%20Time.png)

## Waiting Time - Tempo de espera e Touching Time - Tempo de ação

Olhando para o kanban: temos colunas de ação (fazendo) e colunas de espera (pronto, backlog, 
à fazer, aguardando). O tempo que o item fica nas colunas de espera é chamado de Waiting Time (tempo de espera), e o tempo que o item fica na coluna de ação é chamado de Touching Time (tempo de ação). É comum acreditar que quanto maior o Touching Time e menor o Waiting Time, mais utilização de recursos e um melhor desempenho, o que não é verdade. Estudos de Harvard comprovam que o tempo de espera dobra quando a taxa de ocupa- ção vai de 60% para 80%, dobra novamente de 80% para 90% e dobra mais uma vez quando vai de 90% para 95%. O ideal é balancearmos entre espera e ação para melhorar o desempenho.

![Waiting Time](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/M%C3%A9tricas%20de%20Efici%C3%AAncia/Waiting%20Time.png)

## Flow Efficiency - Fluxo de eficiência

Para sabermos se o nosso fluxo de trabalho está eficiente, utilizamos a métrica de FLOW EFFICIENCY (fluxo de eficiência). Para calculá-lo, basta dividir o Touching Time pela soma entre Waiting Time e Touching Time e depois multiplicar por 100. Vamos exemplificar: um item que demorou 10 dias para ser entregue, dos 10 dias, 7 dias ele ficou em espera e 3 em trabalho, logo a conta seria 3/10 100, e então a eficiência do fluxo para esse item que foi entregue foi de 30%. Por incrível que pareça, na maioria das vezes, as atividades ficam mais tempo em espera do que em ação, e quando a organização não se atenta para isso, geralmente seu fluxo de eficiência fica em torno de 15%, ou seja, 85% do ciclo da atividade é esperando algum processo ou alguma coisa acontecer. Na maioria dos casos, podemos alcançar uma porcentagem muito melhor no fluxo de eficiência e, consequentemente, uma maior redução de Lead Time, concentramos os esforços na resolução das causas raízes de tempo de espera.

![Flow Efficiency](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/M%C3%A9tricas%20de%20Efici%C3%AAncia/Flow%20Efficiency.png)

## WORKING IN PROGRESS (WIP) - Trabalho em progresso

O WORKING IN PROGRESS (trabalho em progresso) é essencial para sabermos a quantidade de itens que estão sendo trabalhados, para assim limitar o WIP e controlar o ritmo da equipe e, consequentemente, melhorar o fluxo de eficiência, pois, em geral, quanto mais itens houver em andamento, maior é o tempo de entrega. O WIP é composto por itens em andamento, itens em espera e itens bloqueados.

## THROUGHPUT - Vazão

O THROUGHPUT (vazão) é a quantidade de itens finalizados em um determinado período de tempo, e geralmente buscamos o maior Throughput com o menor Lead Time possível. A fórmula do cálculo do Throughput é a divisão entre a quantidade de itens finalizados e o tempo, alguns exemplos de cálculo de Throughput são itens entregues por mês ou por semana, Story Points por Sprint, entre outros.

## Cumulative Flow Diagram (CFD) - Diagrama de Fluxo Cumulativo

O **Cumulative Flow Diagram** (CFD) é uma ferramenta visual muito utilizada para representar o progresso de um fluxo de trabalho, no qual há diversos estágios que os itens de trabalho precisam atravessar até serem concluídos. Ele fornece uma visão geral e rápida sobre o que está acontecendo no fluxo, com base nos eixos de **atividades versus tempo**.

![Cumulative Flow](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/M%C3%A9tricas%20de%20Efici%C3%AAncia/Cumulative%20%20Flow.png)

Embora à primeira vista o diagrama possa parecer complexo, ele se torna mais claro com uma explicação passo a passo:

- O **eixo horizontal** representa um **período de tempo** (dias, semanas ou sprints).
- O **eixo vertical** mostra o **acúmulo de itens** no fluxo de trabalho (atividades, tarefas ou histórias de usuário).
- Cada **área colorida** no diagrama representa uma **etapa do fluxo** de trabalho (ex.: backlog, a fazer, fazendo, feito).
- O **espaço horizontal** entre as etapas indica o **ciclo de tempo** (*cycle time*), ou seja, quanto tempo as tarefas levam para avançar entre as etapas.
- O **espaço horizontal** do backlog até o "feito" representa o **lead time**, o tempo total desde que uma tarefa entra no fluxo até ser concluída.
- O **espaço vertical** na área do backlog revela o **tamanho do backlog**, ou seja, quantos itens ainda precisam ser trabalhados.
- O **espaço vertical** entre a etapa de backlog e o "feito" exibe o **WIP** (*work in progress*), que é a quantidade de trabalho em andamento.
- O **espaço vertical** do backlog até imediatamente antes do "feito" mostra a **quantidade de trabalho restante** a ser concluído.

![Cumulative Flow 2](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/M%C3%A9tricas%20de%20Efici%C3%AAncia/Cumulative%20Flow_2.png)

Este diagrama é uma poderosa ferramenta para identificar gargalos no processo e medir a eficiência do fluxo de trabalho, ajudando as equipes a monitorar e otimizar seus processos ao longo do tempo.

Existe alguns exemplos de CFD conhecidos, que já demonstram determinadas características do fluxo de trabalho, eles são:

### Baleia Penteada

Times maduros que utilizam o método Kanban frequentemente apresentam um CFD com o formato de uma **baleia penteada**, onde as fases de trabalho avançam com a mesma velocidade. A parte **verde** do diagrama representa o corpo da baleia, que corresponde à fase de entrega. Quanto mais os "cabelos" da baleia estiverem alinhados ao corpo, **menor é o WIP e o lead time**. Esse modelo de CFD é o ideal para times ágeis, pois indica que o **sistema puxado está funcionando** eficientemente, com etapas de trabalho cujos esforços são equilibrados, levando a um **fluxo estável e rápido** com **baixos cycle time e lead time**.

<p align="center">
  <img src="https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/Fluxo%20de%20Trabalho/BALEIA_PENTEADA_1.png" width="45%" />
  <img src="https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/Fluxo%20de%20Trabalho/BALEIA_PENTEADA_2.png" width="45%" />
</p>

### Cachorro Quente

Esse tipo de CFD revela que há **trabalho acumulado**, e que, com certa frequência, esse trabalho é movido para a próxima fase e concluído rapidamente. Um exemplo comum seria o acúmulo de atividades que foram homologadas e aguardam a implantação. No diagrama, as fases **laranja** e **azul** representam o pão do cachorro-quente, enquanto as fases intermediárias simbolizam a **salsicha e a mostarda**, que são as atividades em execução.

<p align="center">
  <img src="https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/Fluxo%20de%20Trabalho/CACHORRO_QUENTE_1.png" width="45%" />
  <img src="https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/Fluxo%20de%20Trabalho/CACHORRO_QUENTE_2.png" width="45%" />
</p>

### Boca de Jacaré

À medida que o tempo passa, mais itens entram em progresso e ficam acumulados por mais tempo, sugerindo que a capacidade da equipe pode estar sendo ultrapassada. Esse tipo de CFD assume a forma de uma **boca aberta**, onde as fases **laranja** e **azul** lembram a boca de um jacaré. Esse formato indica que há **mais itens em desenvolvimento do que o time pode suportar**, gerando atrasos e gargalos.

<p align="center">
  <img src="https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/Fluxo%20de%20Trabalho/BOCA_JACARE_1.png" width="45%" />
  <img src="https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/Fluxo%20de%20Trabalho/BOCA_JACARE_2.png" width="45%" />
</p>

### Pescoço de Girafa

No caso de equipes que seguem o modelo **Waterfall**, as atividades são realizadas em blocos, o que resulta em **cycle times e lead times** maiores. Consequentemente, o gráfico fica com grandes blocos de tempo, onde cada fase pode ser tão extensa que o diagrama se assemelha ao **pescoço de uma girafa**. Esse formato é típico de fluxos de trabalho em cascata, que são mais rígidos e têm menos flexibilidade em comparação com métodos ágeis.

<p align="center">
  <img src="https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/Fluxo%20de%20Trabalho/PESCO%C3%87O_GIRAFA_1.png" width="45%" />
  <img src="https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/Fluxo%20de%20Trabalho/PESCO%C3%87O_GIRAFA_2.png" width="45%" />
</p>

## Control Chart - Gráfico de Controle

O **Control Chart** (gráfico de controle) é uma ferramenta amplamente utilizada na gestão de processos e na metodologia ágil para monitorar o desempenho de um processo ao longo do tempo. Ele permite visualizar a variação e identificar possíveis desvios no fluxo de trabalho, ajudando as equipes a entender a estabilidade e a capacidade do processo.

![Control Chart](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/M%C3%A9tricas%20de%20Efici%C3%AAncia/Control%20%20Chart.png)

### Componentes do Control Chart

1. **Eixo Horizontal (x):** Representa o tempo, geralmente medido em dias ou sprints, permitindo acompanhar o desempenho ao longo de um período específico.

2. **Eixo Vertical (y):** Mostra o tempo necessário para a conclusão de cada item de trabalho, geralmente o **cycle time** (tempo de ciclo), que é o tempo gasto desde o início até a finalização de uma tarefa.

3. **Linha Central (média):** Uma linha horizontal que representa o tempo médio de ciclo para o processo. Ela oferece uma referência para comparar o desempenho atual com o desempenho histórico.

4. **Linhas de Controle Superior e Inferior:** São limites que definem a variação aceitável do processo. Qualquer ponto fora desses limites pode indicar uma anomalia ou problema que requer atenção.

### Funções do Control Chart

- **Monitoração do Desempenho:** O Control Chart mostra se o processo está dentro dos limites esperados ou se há variações que exigem ajustes.
- **Identificação de Tendências:** Ao observar o gráfico ao longo do tempo, é possível identificar padrões de melhoria ou piora no processo, como aumentos no tempo de ciclo ou acúmulo de tarefas.
- **Detecção de Anomalias:** Pontos fora dos limites de controle (superior e inferior) indicam problemas, como picos de carga ou problemas de fluxo que afetam o processo.
- **Aprimoramento Contínuo:** Ao monitorar e ajustar o processo com base no que é visualizado no Control Chart, as equipes podem otimizar o fluxo de trabalho para manter o ciclo de trabalho estável e eficiente.

### Vantagens do Control Chart

- **Estabilidade do Processo:** Ajuda a manter o processo dentro de padrões aceitáveis, com base na variabilidade natural do fluxo.
- **Identificação de Gargalos:** Facilita a localização de onde ocorrem desvios no tempo de ciclo, permitindo intervenções rápidas.
- **Aperfeiçoamento de Fluxo:** Auxilia na otimização contínua do fluxo de trabalho, garantindo que os esforços sejam eficientes e minimizando o desperdício.

### Diferença entre Control Chart e CFD

Enquanto o **Cumulative Flow Diagram (CFD)** foca em visualizar o acúmulo de itens e o progresso de fases, o **Control Chart** é voltado para monitorar e controlar a variabilidade e estabilidade do tempo de ciclo dos itens no fluxo. O CFD mostra o "quantitativo" (quantos itens), e o Control Chart mostra o "tempo" (quanto tempo para completar cada item).

## MÉTRICAS DE EFICÁCIA (NEGÓCIO)
É essencial em organizações medir como andam os objetivos e as metas, para, se necessário, tomar al- guma ação o quanto antes. Para isso temos as métricas de eficácia.

### ROI (Return on Investment)

Vários projetos podem ser iniciados na empresa e algo que sempre é levantado é qual será o RETURN OF INVESTIMENT (retorno sobre investimento), uma métrica de performance financeira que expressa a relação entre o valor investido em um negócio e o valor obtido em retorno, utilizada para qualificar se um investimento vale a pena ou não financeiramente.
Imagine que você seja o presidente de uma empresa e receba dois projetos, você deve escolher qual dos dois vai iniciar primeiro: a receita esperada do projeto A é de R$ 1.000.000,00 e o do projeto B é de R$ 500.000,00. Pergunta: qual desses você faria primeiro? A resposta correta depende do valor de investi- mento realizado em cada projeto, se o projeto A necessitar de R$ 800.000,00 de investimento, e o pro- jeto B de R$ 200.000,00, podemos aplicar a seguinte fórmula de ROI:

O ROI é expressado em porcentagem, e dado o cenário anterior, o projeto A teria um retorno de investimento de 25%, enquanto o projeto B traria um retorno de investimento de 150%. Com o ROI podemos tomar melhores decisões, as quais talvez sejam essenciais para a organização, e ele deve ser tratado com uma análise cuidadosa, para ser pos- sível identificar as principais fontes de renda do negócio.

![ROI](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/M%C3%A9tricas%20de%20Efic%C3%A1cia/ROI.png)

### NPS (Net Promoter Score)

O **Net Promoter Score (NPS)** é uma métrica utilizada para medir a lealdade e satisfação dos clientes de uma empresa, produto ou serviço. O NPS é baseado em uma única pergunta: "Em uma escala de 0 a 10, qual a probabilidade de você recomendar este produto ou serviço a um amigo ou colega?"

![NPS](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/M%C3%A9tricas%20de%20Efic%C3%A1cia/NPS.png)


### Cálculo do NPS:
1. **Promotores** (nota 9-10): Clientes satisfeitos, dispostos a recomendar.
2. **Neutros** (nota 7-8): Clientes satisfeitos, mas não entusiasmados.
3. **Detratores** (nota 0-6): Clientes insatisfeitos.

Para calcular o NPS, você precisa subtrair a porcentagem de detratores da porcentagem de promotores, calculando, assim, uma pontuação entre -100 e 100.

![Cálculo NPS](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/M%C3%A9tricas%20de%20Efic%C3%A1cia/C%C3%A1lculo%20NPS.png)

De acordo com a porcentagem obtida no NPS, podemos classificar a empresa em quatro níveis, que indicam o quão bem ela está em relação à satisfação dos clientes

![BOM NPS](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/M%C3%A9tricas%20de%20Efic%C3%A1cia/BOM%20NPS.png)


Além de perguntar a pontuação no NPS, você também pode adicionar perguntas extras condicionadas à resposta do entrevistado, para assim colher feedback e conseguir tomar ações:

![Perguntas Adicionais NPS](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/M%C3%A9tricas%20de%20Efic%C3%A1cia/Perguntas%20Adicionais_NPS.png)

O resultado varia de -100 a 100. Quanto maior o NPS, melhor é a lealdade e satisfação dos clientes. Quanto mais alto for o NPS, mais satisfeito estarão os clientes e, consequentemente, mais contribuirão para o crescimento do negócio.


### Churn

O CHURN é uma métrica que informa a porcentagem de clientes que abandonaram o negócio. Sua fór-
mula é a divisão da quantidade de clientes que abandonaram em determinado período pela quantidade
de clientes que existia no início do período. Exemplificando, se o seu negócio possui 300 clientes no ini-
cio do mês, e 15 deles abandonaram, a conta seria (15/300)* 100, totalizando um churn de 5%.

Um dos principais motivos que levam ao churn é a insatisfação do cliente, ele não vê valor no negócio ou opta pela concorrência, porém algumas ações podem ser tomadas para diminuição do churn, como alinhamento de expectativas, entrega de va- lor esperado pelo cliente, boas experiências, aten- ção aos feedbacks e correção rápida de eventuais problemas e erros. É muito importante medir o churn para reduzi-lo ao máximo, pois, dependendo do modelo de negócio, especialmente aqueles que
dependem de assinaturas, eles podem sofrer um impacto direto nas receitas da organização

![CHURN](https://github.com/JonathanFacchinetti/DevOps-Agile-Culture/blob/main/Imagens/M%C3%A9tricas%20de%20Efic%C3%A1cia/CHURN.png)

## Métricas de Atmosfera (Cultural)

### 1. **Turnover**
As métricas de atmosfera, no domínio cultural, têm o objetivo de medir a satisfação em relação a diversos aspectos da organização, buscando tornar o ambiente cada vez mais saudável para o trabalho. O **turnover** (rotatividade de pessoas) está relacionado ao desligamento de funcionários (seja por demissão ou pedido de demissão) e à entrada de novos para substituição. As razões para o desligamento podem ser diversas, e é importante medir essa taxa para identificar possíveis causas, como:

- Insatisfação com o trabalho.
- Problemas na gestão de pessoas.
- Mercado de trabalho aquecido.
- Clima organizacional ruim.
- Inadequação ao perfil da vaga.

Uma alta taxa de turnover impacta negativamente a organização, especialmente quando os funcionários que saem são de alta qualidade ou ocupam cargos-chave, cuja substituição pode levar tempo. Para reduzir o turnover, recomenda-se implementar programas de **onboarding** e **offboarding** eficazes, que integrem os funcionários à empresa, realizar pesquisas de clima organizacional continuamente, e fazer entrevistas de desligamento.

### 2. **Happiness Radar**
O **Happiness Radar** (radar da satisfação) contribui para as pesquisas de clima organizacional, com o objetivo de identificar a satisfação dos profissionais em relação à organização. Essa métrica pode incluir diferentes pontos de avaliação, como processos, ferramentas, entregas, equipe, e a empresa como um todo. Nos times ágeis, o Happiness Radar é frequentemente utilizado nas cerimônias de retrospectiva e pode ser tão simples quanto uma pergunta: "Como você está se sentindo hoje?", ou uma dinâmica mais detalhada com um quadro de avaliação de múltiplos aspectos.

Além de realizar o Happiness Radar periodicamente, é essencial manter e analisar o histórico de mudanças, tomando atitudes conforme necessário para contribuir com a melhoria do ambiente e reduzir o turnover.

---

## Métricas de Qualidade (Técnica)

### 1. **Notificação de Problemas**
Essa métrica refere-se ao número de **bugs** (falhas), defeitos, devoluções de produtos e serviços, bem como o número de chamados ou reclamações. Esses problemas devem ser acompanhados de perto e resolvidos o mais rápido possível. Um problema simples, como uma dúvida sobre o funcionamento de um software, pode gerar custos financeiros para a empresa. Além disso, problemas mais graves, como falhas de segurança, podem expor a organização a prejuízos milionários e afetar negativamente sua imagem no mercado.

### 2. **Cobertura de Testes**
Para reduzir a quantidade de problemas notificados, a métrica de **cobertura de testes** é fundamental. Ela indica a porcentagem de código que está coberta por testes automatizados. Uma baixa cobertura pode aumentar os **débitos técnicos** e as chances de comportamentos inesperados, bugs ou vulnerabilidades de segurança. É importante investir no aumento da cobertura de testes, mas isso não garante, por si só, a qualidade do software. Deve-se focar nas funcionalidades principais (core), automatizar sempre que possível, e reduzir a carga de testes manuais.

### Métricas tóxicas e de vaidade

## Métricas Tóxicas

Ao trabalhar com métricas, é essencial tomar cuidado com as chamadas **métricas tóxicas**. Essas métricas têm como objetivo medir o desempenho individual das pessoas ou comparar a performance de diferentes times, o que, inevitavelmente, gera uma **competição não saudável** e **diminui a colaboração** dentro das equipes.

### Exemplos de Métricas Tóxicas:

- **Tarefas entregues por pessoa**: Medir quantas tarefas uma pessoa finalizou pode criar incentivos para entregar quantidade ao invés de qualidade. Isso também pode desestimular a troca de conhecimento, já que a pessoa buscará entregar mais tarefas sozinha.
  
- **Quantidade de bugs corrigidos**: Similar à métrica de tarefas entregues, medir a quantidade de bugs corrigidos individualmente pode fazer com que as pessoas se concentrem em números, sem se preocupar com a complexidade dos problemas que estão sendo resolvidos.

- **“Funcionário do Mês”**: A ideia de reconhecer um único indivíduo como o “melhor” gera uma competitividade direta entre os membros da equipe. Isso pode diminuir a colaboração, já que cada pessoa busca destacar-se e ser premiada.

Essas métricas acabam estimulando a **competitividade entre as pessoas**, que passarão a querer bater metas e ser melhores que os outros. O resultado disso é uma **redução significativa da colaboração**, pois os colegas de trabalho passam a ser vistos como concorrentes.

### Comparação Entre Times

Outro erro comum é utilizar as métricas de um time para **comparar com outro time**. Na maioria dos casos, os times têm contextos completamente diferentes, como projetos distintos, complexidades variadas ou objetivos diferentes. Cada time possui suas próprias **características específicas**, e ao compará-los, novamente, gera-se mais competição e menos colaboração entre equipes.

---

## Métricas de Vaidade

As **métricas de vaidade** são outro tipo de métrica perigosa, pois apresentam números impressionantes que podem ocultar informações mais relevantes ou verdadeiras. Elas criam uma falsa sensação de sucesso e, frequentemente, não levam a ações que realmente melhorem o produto ou processo.

### Exemplos de Métricas de Vaidade:

- **Número de downloads de um aplicativo**: Pode parecer uma métrica de sucesso, mas não indica se o app está sendo bem utilizado ou apreciado. Um aplicativo pode ter milhares de downloads e, ao mesmo tempo, **avaliar mal entre os usuários**.

- **Número de visitantes no site**: Um site pode ter muitos acessos, mas se esses visitantes não estiverem engajando ou realizando ações valiosas (como compras ou assinaturas), o número de acessos isoladamente não é uma métrica relevante.

- **Quantidade de seguidores nas redes sociais**: Um alto número de seguidores não reflete necessariamente o sucesso de uma campanha ou a qualidade do engajamento com o público. Seguidores podem ser inativos ou não interagir com o conteúdo.

- **Número de registros no banco de dados**: A quantidade de registros não representa, por si só, o valor de uma base de dados. O importante é a **qualidade e relevância dos dados**, e não apenas o volume.

Essas métricas indicam apenas números brutos e podem esconder a realidade do desempenho ou da satisfação dos usuários. É fundamental substituí-las por métricas que realmente **indiquem valor** ou **impacto significativo** no projeto ou produto.

---
## Conclusão

As métricas, em todos os seus domínios na agilidade, exercem um papel fundamental para a organização. Sem elas, ficamos "cegos" e a melhoria contínua é limitada. Entretanto, lembre-se de que **"Métricas Moldam Comportamentos"**, pois, a partir do momento em que é dito que uma pessoa, ou o ambiente, está sendo medido — ou, no pior cenário, como essa pessoa será medida — é muito comum que ela adote um comportamento que atenda às expectativas dessas medições.

Esse aviso é crucial para que, ao trabalharmos com métricas, tenhamos o cuidado de não utilizar indicadores que não agregam valor e que muitas vezes atrapalham o dia a dia, contaminando o ambiente e reduzindo a agilidade.

Sempre que for escolher uma métrica, utilize aquelas que realmente façam sentido e tragam benefícios à organização. Dessa forma, será possível identificar, analisar e tomar ações para a melhoria contínua do negócio.
