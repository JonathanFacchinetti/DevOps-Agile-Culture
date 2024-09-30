# Métricas de Eficiência (Organizacional)

O trabalho na organização começa desde a hipótese de algo até o atingimento de um objetivo, e no meio do caminho dexistem diversas etapas com diferentes áreas da organização. As métricas de eficiência são o melhor caminho para se determinar se estamos trabalhando da melhor forma e identificar gargalos, solucionando-os em busca da melhoria continua.

## Lead Time - Tempo de espera

Considerado como uma das métricas de eficiência mais importantes, o Lead Time (Tempo de espera) nos traz informações sobre o número de dias (tempo) entre o início e o fim do processo de entrega. Se o objetivo for construir uma ponte, por exemplo, o tempo de dias que decorre desde o início da ideia, passando pela construção até chegar a finalização da ponte é o nosso lead time. No mundo organizacional, o lead time está relacionado ao *time to market*, que é o tempo que um produto leva desde a sua concepção até que ele esteja totalmente disponível para venda ou consumo. Em geral, buscamos ter o menor lead time possível, para assim entregar e obter feedback o quanto antes. Existe uma discussão na comunidade sobre se o lead time se refere apenas ao tempo do trabalho do time de desenvolvimento; no quadro kanban, por exemplo, seria do backlog quando a história fosse criada até a história ser considerada concluída (done). Para não restar dúvidas, é importante definir com a organização o que ela considerada Lead Time

## Cycle Time - Tempo do ciclo ou Local Lead Time - Tempo de espera local

O Lead Time olha para o tempo total do processo de entrega, e como normalmente busca-se diminuir esse tempo, é necessário identificar e analisar cada tempo específico de determinada etapa e, assim, realizar alguma ação, para isso utilizamos o CYCLE TIME (tempo do ciclo), também chamado de LOCAL LEAD TIME (tempo de espera local), que nos dá a informação entre o início e o fim de uma ou mais etapas do processo.

## Waiting Time - Tempo de espera e Touching Time - Tempo de ação

Olhando para o kanban: temos colunas de ação (fazendo) e colunas de espera (pronto, backlog, 
à fazer, aguardando). O tempo que o item fica nas colunas de espera é chamado de Waiting Time (tempo de espera), e o tempo que o item fica na coluna de ação é chamado de Touching Time (tempo de ação). É comum acreditar que quanto maior o Touching Time e menor o Waiting Time, mais utilização de recursos e um melhor desempenho, o que não é verdade. Estudos de Harvard comprovam que o tempo de espera dobra quando a taxa de ocupa- ção vai de 60% para 80%, dobra novamente de 80% para 90% e dobra mais uma vez quando vai de 90% para 95%. O ideal é balancearmos entre espera e ação para melhorar o desempenho.

## Flow Efficiency - Fluxo de eficiência

Para sabermos se o nosso fluxo de trabalho está eficiente, utilizamos a métrica de FLOW EFFICIENCY (fluxo de eficiência). Para calculá-lo, basta dividir o Touching Time pela soma entre Waiting Time e Touching Time e depois multiplicar por 100. Vamos exemplificar: um item que demorou 10 dias para ser entregue, dos 10 dias, 7 dias ele ficou em espera e 3 em trabalho, logo a conta seria 3/10 100, e então a eficiência do fluxo para esse item que foi entregue foi de 30%. Por incrível que pareça, na maioria das vezes, as atividades ficam mais tempo em espera do que em ação, e quando a organização não se atenta para isso, geralmente seu fluxo de eficiência fica em torno de 15%, ou seja, 85% do ciclo da atividade é esperando algum processo ou alguma coisa acontecer. Na maioria dos casos, podemos alcançar uma porcentagem muito melhor no fluxo de eficiência e, consequentemente, uma maior redução de Lead Time, concentramos os esforços na resolução das causas raízes de tempo de espera.

## WORKING IN PROGRESS (WIP) - Trabalho em progresso

O WORKING IN PROGRESS (trabalho em progresso) é essencial para sabermos a quantidade de itens que estão sendo trabalhados, para assim limitar o WIP e controlar o ritmo da equipe e, consequentemente, melhorar o fluxo de eficiência, pois, em geral, quanto mais itens houver em andamento, maior é o tempo de entrega. O WIP é composto por itens em andamento, itens em espera e itens bloqueados.

## THROUGHPUT - Vazão

O THROUGHPUT (vazão) é a quantidade de itens finalizados em um determinado período de tempo, e geralmente buscamos o maior Throughput com o menor Lead Time possível. A fórmula do cálculo do Throughput é a divisão entre a quantidade de itens finalizados e o tempo, alguns exemplos de cálculo de Throughput são itens entregues por mês ou por semana, Story Points por Sprint, entre outros.

## Cumulative Flow Diagram (CFD) - Diagrama de Fluxo Cumulativo

O **Cumulative Flow Diagram** (CFD) é uma ferramenta visual muito utilizada para representar o progresso de um fluxo de trabalho, no qual há diversos estágios que os itens de trabalho precisam atravessar até serem concluídos. Ele fornece uma visão geral e rápida sobre o que está acontecendo no fluxo, com base nos eixos de **atividades versus tempo**.

Embora à primeira vista o diagrama possa parecer complexo, ele se torna mais claro com uma explicação passo a passo:

- O **eixo horizontal** representa um **período de tempo** (dias, semanas ou sprints).
- O **eixo vertical** mostra o **acúmulo de itens** no fluxo de trabalho (atividades, tarefas ou histórias de usuário).
- Cada **área colorida** no diagrama representa uma **etapa do fluxo** de trabalho (ex.: backlog, a fazer, fazendo, feito).
- O **espaço horizontal** entre as etapas indica o **ciclo de tempo** (*cycle time*), ou seja, quanto tempo as tarefas levam para avançar entre as etapas.
- O **espaço horizontal** do backlog até o "feito" representa o **lead time**, o tempo total desde que uma tarefa entra no fluxo até ser concluída.
- O **espaço vertical** na área do backlog revela o **tamanho do backlog**, ou seja, quantos itens ainda precisam ser trabalhados.
- O **espaço vertical** entre a etapa de backlog e o "feito" exibe o **WIP** (*work in progress*), que é a quantidade de trabalho em andamento.
- O **espaço vertical** do backlog até imediatamente antes do "feito" mostra a **quantidade de trabalho restante** a ser concluído.

Este diagrama é uma poderosa ferramenta para identificar gargalos no processo e medir a eficiência do fluxo de trabalho, ajudando as equipes a monitorar e otimizar seus processos ao longo do tempo.

Existe alguns exemplos de CFD conhecidos, que já demonstram determinadas características do fluxo de trabalho, eles são:

### Baleia Penteada

Times maduros que utilizam o método Kanban frequentemente apresentam um CFD com o formato de uma **baleia penteada**, onde as fases de trabalho avançam com a mesma velocidade. A parte **verde** do diagrama representa o corpo da baleia, que corresponde à fase de entrega. Quanto mais os "cabelos" da baleia estiverem alinhados ao corpo, **menor é o WIP e o lead time**. Esse modelo de CFD é o ideal para times ágeis, pois indica que o **sistema puxado está funcionando** eficientemente, com etapas de trabalho cujos esforços são equilibrados, levando a um **fluxo estável e rápido** com **baixos cycle time e lead time**.

### Cachorro Quente

Esse tipo de CFD revela que há **trabalho acumulado**, e que, com certa frequência, esse trabalho é movido para a próxima fase e concluído rapidamente. Um exemplo comum seria o acúmulo de atividades que foram homologadas e aguardam a implantação. No diagrama, as fases **laranja** e **azul** representam o pão do cachorro-quente, enquanto as fases intermediárias simbolizam a **salsicha e a mostarda**, que são as atividades em execução.

### Boca de Jacaré

À medida que o tempo passa, mais itens entram em progresso e ficam acumulados por mais tempo, sugerindo que a capacidade da equipe pode estar sendo ultrapassada. Esse tipo de CFD assume a forma de uma **boca aberta**, onde as fases **laranja** e **azul** lembram a boca de um jacaré. Esse formato indica que há **mais itens em desenvolvimento do que o time pode suportar**, gerando atrasos e gargalos.

### Pescoço de Girafa

No caso de equipes que seguem o modelo **Waterfall**, as atividades são realizadas em blocos, o que resulta em **cycle times e lead times** maiores. Consequentemente, o gráfico fica com grandes blocos de tempo, onde cada fase pode ser tão extensa que o diagrama se assemelha ao **pescoço de uma girafa**. Esse formato é típico de fluxos de trabalho em cascata, que são mais rígidos e têm menos flexibilidade em comparação com métodos ágeis.

## Control Chart - Gráfico de Controle

## Control Chart - Gráfico de Controle

O **Control Chart** (gráfico de controle) é uma ferramenta amplamente utilizada na gestão de processos e na metodologia ágil para monitorar o desempenho de um processo ao longo do tempo. Ele permite visualizar a variação e identificar possíveis desvios no fluxo de trabalho, ajudando as equipes a entender a estabilidade e a capacidade do processo.

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

