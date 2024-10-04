# Desvendendo o UML

## Introdução
O desenvolvimento de software é uma atividade bastante complexa, e em razão disso, existe dificuldades e surgem vários problemas quando não há um padrão comum de interpretação para a equipe envolvida. Para então, é necessário desenvolver o software sem que haja um retrabalho, cuja manutenção no futuro seja fácil e no qual todos os envolvidos interpretem a mesma linguagem. A UML propõe a construção de diagramas para o desenvolvimento de sistemas orientados a objetos a fim de facilitar, por meio de notação visual, uma representação comum em determinado momento do desenvolvimento de software. 

## Conceito de UML

**Conforme Guedes afirma**:
"A UML - Unified Modeling Language (Linguagem de Modelagem Unificada) - É uma linguagem visual utilizada para modelar softwares baseados no paradigma da orientação objetos. É uma linguagem de modelagem de propósito geral que pode ser aplicada a todos os domínios da aplicação. Esta linguagem tornou-se, nos últimos anos, a linguagem padrão de modelagem adotada internacionalmente pela indústria de engenharia de software"
- Guedes (2011, p.8)

A UML é uma linguagem com padrões visuais para modelar sistemas orientados a objetos. 

## Histórico de desenvolvimento de sistemas

Nas décadas de 1950 e de 1960, o desenvolvimento de sistema era tecnicista, ou seja, o usuário solicitava ao programador de um sistema, e este, somente com a visão da necessidade estabelecida, programava sem metodologia ou padrão, tudo era feito *ad hoc* (direto ao assunto ou direto ao que interessa). De acordo com Bezerra (2007, p.13), "talvez o uso deste termo denote a abordagem da primeira fase de desenvolvimento de sistema, no qual não havia planejamento inicial".

A análise foi concebida na década de 1970 e surgiu com o objetivo de construir sistemas mais eficientes e eficazes, por meio do uso de modelos e padrões estruturados para facilitar o entendimento da necessi- dade do usuário, pois antes do uso da análise, os sistemas não atendiam adequadamente a real necessi- dade dos usuários, além dos projetos que extrapolavam os prazos e os orçamentos por falta de entendi- mento da necessidade do usuário, o "ouvir" e programar sem estudo prévio causava grandes problemas no desenvolvimento de sistemas. Portanto, antes da análise não havia padrões, ferramentas, técnicas nem métodos para o desenvolvimento de sistemas.

De acordo com Bezerra
"O rápido crescimento da capacidade computacional das máquinas resultou na demanda por sistemas de software cada vez mais complexos. Portanto, o surgimento destes sistemas complexos resultou na necessidade de reavaliação das formas de desenvolvimento de sistema, consequentemente, o surgimento de metodologias, práticas, técnicas e padrões para a modelagem de sistema".
- Bezerra (2007, p.13)

Na década de 1980, com o surgimento dos computadores pessoas, os PCs, aumentou a necessidade de sistemas mais complexos, a análise estruturada se consolidou na primeira metade dessa década. Em 1980, Edward Yourdon lançou o livro Análise Estruturada Moderna, que se tornou referência neste assunto. A análise estrutural foi utilizada para modelagem de sistemas estruturados por meio da representação gráfica de Diagramas de Fluxos de Dados, por exemplo.

Na década de 1990, surgiu um novo paradigma para a modelagem de sistemas orientados a objetos. Para essa década, as principais técnicas para modelagem de sistemas são: OOSE (Object Oriented Software Engineering), de Ivair Jacobson; o OMT (Object Modeling Technique), de James Rumbaugh; e o método de Grady Booch

| Técnica de modelagem         | Descrição                                                                 |
|------------------------------|---------------------------------------------------------------------------|
| Ivair Jacobson - **OOSE**     | Ênfase em casos de uso - descrição do cenário. Demonstrar interação do usuário com o sistema. |
| James Rumbaugh - **OMT**      | Representação de objetos, classes e relacionamentos.                      |
| Grady Booch - **Booch**       | Sistema deve ser analisado por meio de várias visões, para cada uma deve haver um diagrama.    |

_Modelagem de sistema orientado a objetos na década de 1990_


# Histórico UML

Entre 1991 e 1995, começou o desenvolvimento de técnicas para modelagem de sistemas orientados a objetos. Os principais contribuintes foram: **Ivair Jacobson**, **James Rumbaugh** e **Grady Booch**, que reaproveitaram as melhores características e artefatos das técnicas propostas (conforme Figura Histórico da Orientação a Objetos até o Surgimento da UML) para o desenvolvimento da UML. Inicialmente chamada de **UM** (*Unified Method*), foi apenas com a entrada de Booch, quando os três trabalharam na empresa **Rational Software**, que as propostas foram unificadas e surgiu a **UML** (*Unified Modeling Language*).

Em 1997, a **OMG** (*Object Management Group*), uma organização que define e ratifica a padronização de assuntos relacionados à orientação a objetos, aprovou e adotou o padrão UML para a modelagem de sistemas orientados a objetos. Desde então, esse padrão tem grande aceitação no mercado e na comunidade de desenvolvedores.

A **UML** se tornou uma linguagem ou notação visual que permite representar os paradigmas da orientação a objetos para modelagem de sistemas. Por meio dessa notação visual com diagramas, é possível representar várias perspectivas do sistema.

## Por que utilizar diagramas para modelar sistemas?

Os diagramas são notações visuais que facilitam a interpretação lógica do sistema em vários aspectos. Eles fornecem uma representação objetiva do sistema. Como diz o ditado: "Uma imagem vale mais que mil palavras."

## Mas, afinal, o que é e o que não é UML?

A **UML** é uma linguagem visual para construir, documentar e especificar sistemas orientados a objetos. Não deve ser confundida com uma linguagem de programação, pois não tem relação com o processo de desenvolvimento e pode ser definida como um padrão de notação visual.

A UML é responsável por toda a documentação da arquitetura do sistema, especifica os requisitos e auxilia nos casos de teste. Ela oferece suporte no planejamento e gerenciamento de cada versão do software.

**Não confunda UML com:** 
- Linguagem de programação
- Método
- Metodologia

## Quais são as razões para a construção de modelos visuais?

- Facilita a comunicação entre as pessoas envolvidas no projeto de software.
- Reduz o tempo e o custo de desenvolvimento.
- Facilita a futura manutenção do sistema.
- Lida com a complexidade do sistema.
- Ajuda a controlar a complexidade.
- Garante o gerenciamento dos entregáveis.
- Auxilia no gerenciamento de mudanças.
- Reduz ambiguidades.

# Diagramas da UML

A UML (Unified Modeling Language) utiliza o conceito de **visões**, que define o objetivo de cada diagrama dentro do contexto de desenvolvimento de software. Na UML, temos dois tipos principais de diagramas: **estáticos** e **dinâmicos**.

## Diagramas Dinâmicos
Os diagramas dinâmicos representam o comportamento e a interação entre os elementos do sistema em tempo de execução. Eles incluem:

- **Diagrama de Atividade**
- **Diagrama de Caso de Uso**
- **Diagrama de Fluxo de Informação**
- **Diagrama de Máquina de Estado**

### Diagramas de Interação:
- **Diagrama de Sequência**
- **Diagrama de Comunicação**
- **Diagrama de Tempo**
- **Diagrama de Visão Geral da Interação**

## Diagramas Estáticos
Os diagramas estáticos descrevem a estrutura estática do sistema, mostrando as classes, objetos e seus relacionamentos. Esses diagramas incluem:

- **Diagrama de Classe**
- **Diagrama de Objetos**
- **Diagrama de Pacotes**
- **Diagrama de Estrutura Composta**
- **Diagrama de Componentes**
- **Diagrama de Implantação**
- **Diagrama de Perfil**

De acordo com Bezerra (2007,p.16), "os autores da UML propõem que um sistema pode ser desenvolvido a partir de cinco visões (Booch et al., 2006), e cada uma dá ênfase aos diferentes aspectos do sistema".

# Diagramas UML

Os diagramas que serão exemplificados a seguir trazem o objetivo e a visão propostos para cada um deles.

## Diagrama de Atividades

- **Objetivo**: É um diagrama dinâmico que representa o fluxo e a sequência de tarefas de um processamento.
- **Visão de Concorrência**: Trata da divisão do sistema em processos e processadores. Permite uma melhor utilização do ambiente onde o sistema se encontrará, especialmente se o mesmo possui exceções paralelas e gerenciamentos assíncronos.

## Diagrama de Caso de Uso

- **Objetivo**: É um diagrama dinâmico que representa um conjunto de ações (casos de uso) que os sistemas devem executar em interação com um ou mais usuários externos do sistema (atores), a fim de fornecer resultados para as partes interessadas do(s) sistema(s).
- **Visão (use-case)**: Descreve a funcionalidade do sistema executada pelos atores externos (usuários).

## Diagrama de Classe

- **Objetivo**: É um diagrama estático que representa a estrutura lógica do sistema, subsistema ou componente projetado como classes e interfaces relacionadas, com suas características, restrições e associações, generalizações, etc.
- **Visão Lógica ou de Projeto**: Descreve o sistema internamente, dando suporte à visão estrutural do sistema.

## Diagrama de Sequência

- **Objetivo**: É um diagrama dinâmico que representa a ordem da troca de mensagens entre os objetos.
- **Visão de Concorrência**: Trata da divisão do sistema em processos e processadores. Permite uma melhor utilização do ambiente onde o sistema se encontrará, se ele possui exceções paralelas e gerenciamentos assíncronos.

## Diagrama de Máquina de Estados

- **Objetivo**: É um diagrama dinâmico que representa a situação em que um objeto se encontra em determinado momento durante o processamento. Um objeto pode passar por diversos estados.
- **Visão de Concorrência**: Trata da divisão do sistema em processos e processadores. Permite uma melhor utilização do ambiente onde o sistema se encontrará, especialmente se o mesmo possui exceções paralelas e gerenciamentos assíncronos.

## Diagrama de Componentes

- **Objetivo**: É um diagrama estático que representa a estrutura física da implementação e é construído como parte da especificação da estrutura do software.
- **Visão de Componentes**: Trata da descrição da implementação dos módulos e suas dependências. São desenvolvidos por desenvolvedores com maior experiência em programação ou por arquitetos de software.

A partir da UML 2, o componente que era representado por um retângulo com dois retângulos menores, conforme exemplo da figura acima, foi substituído por um retângulo contendo internamente o antigo símbolo, conforme exemplo abaixo no Diagrama de Componente.

## Diagrama de Implantação

- **Objetivo**: É um diagrama estático que representa os elementos de configuração do processamento em tempo de execução, ou seja, uma visão dos componentes de software.
- **Visão de Organização**: Mostra a organização física do sistema, os computadores, os periféricos e como eles se conectam entre si.

## Diagrama de Objetos

- **Objetivo**: É um diagrama estático que representa a relação dos objetos com base nas instâncias criadas a partir do diagrama de classe de análise.
- **Visão Lógica ou de Projeto**: Descreve o sistema internamente, dando suporte à visão estrutural do projeto.

## Diagrama de Colaboração

- **Objetivo**: Foca na ordenação estrutural em que as mensagens de um sistema são trocadas entre os objetos.
- **Visão Lógica ou de Projeto**: Exibe de forma explícita a colaboração dinâmica entre os objetos.

## Diagrama de Pacotes

- **Objetivo**: Ilustra a arquitetura de um sistema mostrando o agrupamento de suas classes.
- **Visão Lógica ou de Projeto**: Descreve as partes e/ou pacotes do sistema divididos em agrupamentos lógicos.

## Diagrama de Perfil

- **Objetivo**: Define novos elementos UML.
- **Visão Lógica ou de Projeto**: Estende diagramas existentes com a inclusão de estruturas customizadas.
