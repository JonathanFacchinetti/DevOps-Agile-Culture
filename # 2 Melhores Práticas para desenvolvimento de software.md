# Melhores Práticas para Desenvolvimento de Software

## Introdução

Na era moderna, a tecnologia da informação e seus respectivos softwares, serviços e aplicativos desempenham um papel cada vez mais predominante no dia a dia da sociedade. Para o desenvolvimento desses, utilizamos a metodologia de desenvolvimento de software, que é um conjunto de métodos coordenados para se alcançar um objetivo por meio de uma dinâmica iterativa, visando à qualidade e à produtividade dos projetos.

> Inicialmente, vamos conhecer a história e sua influência nas metodologias modernas, antes de abordarmos as metodologias atuais.

Após a Segunda Guerra Mundial, a empresa japonesa Toyota Motors identificou a necessidade de tornar a produção mais eficiente e, para tal, desenvolveu um sistema de produção que fornecia melhor qualidade, menor custo e menor tempo de entrega. Visando diminuir o desperdício, utilizou o princípio de Jidoka (capacidade de detectar uma anormalidade rapidamente e interromper imediatamente o trabalho, evitando desperdícios, otimizando o processo e garantindo a qualidade do produto final) e o conceito de just-in-time (produzir o que é necessário, no momento necessário e na quantidade necessária), por meio da prática Kanban (termo de origem japonesa que significa literalmente "cartão" ou "sinalização"), que utiliza cartões de informação para controlar a produção de acordo com a demanda. Todo esse processo industrial ficou conhecido como TPS (Toyota Production System) e possui grande influência nas metodologias que serão abordadas neste estudo.

Saindo do modelo de desenvolvimento industrial, no modelo de desenvolvimento de software, algo muito utilizado foi o Modelo em Cascata (Waterfall Model), uma sequência de fases no desenvolvimento de software que são: análise e definição dos requisitos, design, desenvolvimento, testes e manutenção. Porém, o modelo em Cascata apresenta alguns desafios, como:

- Escopo engessado no começo do projeto: Visto que mudanças no mundo acontecem cada vez mais rápido, uma mudança na demanda pode tornar o produto irrelevante até o final do projeto;
- Desperdício com funcionalidades desnecessárias: Como tudo precisa ser definido no começo, o máximo de funcionalidades será solicitado, mesmo sem a certeza de sua necessidade;
- Entregas lentas: Apenas após um longo período de planejamento, execução e testes de grandes blocos de trabalho é que veremos alguma entrega, que, porventura, pode ser algo de pouco valor no momento;
- Baixa transparência: Manter o envolvimento de todos apenas com processos e extensas documentações não é algo motivador. Provavelmente, algumas pessoas não vão querer ler tudo para executar parte do trabalho, logo, não estarão cientes de todo o projeto com clareza.

Para trabalhar com o desenvolvimento de software de forma mais adequada, na privavera de 2000 um grupo de líderes da comunidade do Extreme Programming (XP - Metodologia que será abordada mais a frente) se reuniram para discutir o processo de desenvolvimento com XP; No decorrer da reunião chegaram a um concenso sobre pontos importantes referentes ao desenvolvimento de software e decidiram escrever um documento que serviria como guia aos novos processos de desenvolvimento ágil de software, o famoso Manifesto Ágil

## Manifesto Ágil

O Manifesto Ágil possui 4 valores e 12 princípios. Note que nas frases, mesmo havendo valores nos itens à direita, a valorização é maior nos itens da esquerda:

- **Indivíduos e interações** mais que processos e ferramentas
- **Software em funcionamento** mais que documentação abrangente
- **Colaboração com o cliente** mais que negociação de contratos
- **Responder a mudanças mais** que seguir um plano

### Valores

- **Indivíduos e interações** mais que processos e ferramentas: O desenvolvimento de software é uma atividade humana e que problemas de comunicação podem ser resolvidos com qualidade na interação entre os envolvidos. Os processos e ferramentas devem cumprir seu papel de forma simples e útil, mas sem "passar por cima" das pessoas.
- **Software em funcionamento** mais que documentação abrangente: O software funcionando é um indicador de sucesso e é o que o cliente espera, a documentação do mesmo deve ser algo que agregue valor e com informações necessárias.
- **Colaboração com o cliente** mais que negociação de contratos: A colaboração com o cliente é algo fundamental para o sucesso do desenvolvimento do software, o trabalho em equipe e a tomada de decisões em conjunto contribuem para alcançar um único objetivo. 
- **Responder a mudanças mais** que seguir um plano: O desenvolvimento de software é algo complexo e possui alta incerteza, nessas situações devemos aprender com as situações ocorridas e adaptar o plano sempre que possível.

Com o Manifesto Ágil escrito, foi criada a *Agile Alliance*, uma organização sem fins lucrativos que busca disseminar o conhecimento e promover discussões sobre métodos ágeis, como o Scrum, Kanban e XP, que têm em suas bases os valores e princípios do Manifesto Ágil. Muitas pessoas acreditam que as metodologias ágeis são "ágeis" porque são rápidas e entregam funcionalidades o quanto antes. Na verdade, a agilidade simboliza a capacidade de adaptação a mudanças. A velocidade nas entregas é uma consequência que ocorre quando utilizamos adequadamente as metodologias, que serão abordadas nesse estudo. 
