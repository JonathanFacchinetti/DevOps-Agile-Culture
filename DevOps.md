# DevOps

DevOps é uma cultura que adota práticas e ferramentas para aumentar a capacidade de uma organização de desenvolver e entregar softwares, serviços, aplicativos e outros produtos de tecnologia com alta velocidade, sem comprometer a estabilidade.

Quando uma organização adota a cultura DevOps, o ritmo de entrega dos produtos é mais rápido do que o de empresas que utilizam processos tradicionais de desenvolvimento de software e gerenciamento de infraestrutura.

Com a adoção da cultura DevOps, as equipes de desenvolvimento e operações, que antes eram tratadas de forma isolada, passam a trabalhar de forma integrada. Essas equipes se combinam em um único time multidisciplinar, promovendo o compartilhamento de conhecimentos e uma compreensão mais ampla dos processos de desenvolvimento e operação.

Os administradores de sistemas (sysadmins) são envolvidos desde o início do ciclo de desenvolvimento do software, participando do planejamento e da construção, enquanto os desenvolvedores acompanham todo o ciclo de vida do software, incluindo as etapas de entrega e o monitoramento do ambiente de produção. Esse envolvimento contínuo de ambas as partes ajuda a garantir que o software funcione corretamente em produção e que as necessidades de operação sejam atendidas desde a concepção.

Esse movimento cria um ambiente de aprendizado colaborativo, no qual desenvolvedores e sysadmins trocam experiências e conhecimentos de suas respectivas áreas. Como exemplo, em um ambiente DevOps, os desenvolvedores podem aprender mais sobre como a infraestrutura de TI funciona, ajudando-os a criar código mais robusto e adequado ao ambiente de produção. Ao mesmo tempo, os sysadmins aprendem mais sobre o processo de desenvolvimento e podem automatizar processos de deploy e gerenciamento de infraestrutura usando ferramentas como Docker, Kubernetes ou Ansible, melhorando o fluxo de trabalho e reduzindo erros manuais.

Essa integração ajuda a eliminar os gargalos comuns entre as duas áreas, aumentando a eficiência e a qualidade das entregas. Além disso, a colaboração contínua facilita a resolução de problemas de forma mais rápida, pois ambas as equipes entendem melhor os desafios e necessidades umas das outras.

## Benefícios do DevOps

- Aumento da velocidade de entrega
- Escalabilidade
- Velocidade
- Colaboração contínua
- Confiabilidade
- Segurança

Para promover a cultura DevOps, existem algumas práticas principais que ajudam as organizações a inovar mais rapidamente por meio da automação e da simplificação dos processos de desenvolvimento de software e gerenciamento de infraestrutura. A maioria dessas práticas é realizada com o auxílio de algumas ferramentas.

A seguir, são listadas as melhores práticas da cultura DevOps:

### Infraestrutura como código:
É uma prática que utiliza técnicas de desenvolvimento de código e permite o controle de versão e integração contínua da infraestrutura, por meio de APIs, para que os desenvolvedores e sysadmins trabalhem com a infraestrutura de modo programático, em vez de instalar e configurar manualmente. Isso otimiza o tempo das equipes, uma vez que o código da infraestrutura pode ser reaproveitado e, quando atualizado, replicado para todos os ambientes que utilizam esse trecho de código.

### Arquitetura de microsserviços:
Representa um conjunto de pequenos serviços que se interligam para construir um sistema. Cada serviço possui um contexto único de negócio, é executado de forma individual e independente e se comunica com outros serviços por meio de uma interface leve, na maioria dos casos baseada em HTTP.

### Integração contínua:
A integração contínua é uma prática de desenvolvimento que permite a execução de testes sempre que as alterações de código são enviadas para o repositório central. Os principais objetivos da integração contínua são encontrar e corrigir os erros mais rapidamente a cada alteração, melhorando a qualidade do software e reduzindo o tempo necessário para validação.

### Entrega contínua:
A entrega contínua é uma prática que permite ao desenvolvedor, ao realizar as alterações de código, utilizar a integração contínua para a realização dos testes necessários e preparar automaticamente as modificações para uma entrega em produção. Quando a integração contínua é implementada adequadamente, os times terão um pacote de entrega confiável pronto para ser implantado a cada alteração ou conjunto de alterações enviadas para o repositório central.

### Monitoração, alarme, log e indexação:
Realizar logs das informações das aplicações e da infraestrutura é essencial para realizar o monitoramento e gerar alarmes. Ao capturar, indexar e analisar os logs gerados pelos aplicativos e pela infraestrutura, é possível entender como as alterações ou atualizações estão afetando o ambiente e seus usuários, facilitando a rastreabilidade e fornecendo maior clareza sobre as causas dos problemas. Com os logs indexados, é possível criar dashboards de acompanhamento em tempo real e programar alarmes de acordo com determinadas situações do ambiente.

### Comunicação e colaboração:
O aumento da comunicação, colaboração e compartilhamento de experiências é um dos principais aspectos culturais do DevOps. O uso de práticas e ferramentas contribui para que as equipes definam normas culturais sólidas em relação ao compartilhamento de informações e processos de trabalho. Com a unificação das equipes, todos passam a trabalhar juntos, seguindo um objetivo comum.

## Estágios e ferramentas DevOps

### Planejamento:
Na fase de planejamento, os desenvolvedores e sysadmins interagem para estimar e dividir as atividades necessárias para a entrega. É essencial a utilização de práticas ágeis, como Scrum ou Kanban, para organizar melhor as tarefas e otimizar o fluxo de trabalho. Isso permite maior visibilidade sobre o que cada integrante está fazendo, facilita a priorização de tarefas e possibilita ajustes contínuos conforme o projeto evolui.

### Desenvolvimento ou codificação:
Na etapa de desenvolvimento, com as atividades definidas, os times começam a codificação tanto do software quanto da infraestrutura como código (IaC - Infrastructure as Code). Nessa fase, utilizamos o Git, um sistema de controle de versões distribuído, que permite que várias pessoas colaborem no desenvolvimento simultâneo, mantendo o histórico de alterações de forma organizada. Para documentar o sistema de forma colaborativa, usamos o Confluence e o Jira para organizar e acompanhar as atividades da equipe. Isso garante que todo o ciclo de desenvolvimento seja gerenciado em um único lugar, vinculando tarefas, repositórios Git e documentação.

### Construção (Build):
Com o código desenvolvido, é necessário realizar o processo de construção (build), no qual o código-fonte e suas dependências são baixados do repositório central, compilados e empacotados em uma versão pronta para testes. Alguns testes básicos, como os de compilação e formatação de código, são realizados nesta etapa. Se houver falhas, o processo de build é interrompido. Ferramentas como Apache Maven e Gradle automatizam a compilação e o gerenciamento de dependências. Enquanto o Maven usa arquivos XML para configuração, o Gradle utiliza scripts Groovy, permitindo maior flexibilidade.

### Teste:
Na fase de testes, com a aplicação do DevOps, são realizados tanto testes de software quanto de infraestrutura. Testes como unitários, de fumaça (smoke test), de integração, regressão e ponta a ponta são executados para o código. Ferramentas como JUnit são utilizadas para testes unitários, e o Selenium para testes de interface e fluxo ponta a ponta. Para a infraestrutura, utilizamos ferramentas como o Testinfra, que validam se a infraestrutura está configurada corretamente e funcionando como esperado.

### Lançamento/Entrega:
Após o desenvolvimento, testes e empacotamento, o software está pronto para o lançamento. Com a cultura DevOps, esse processo é automatizado por ferramentas de pipeline de entrega, como Jenkins e CodeShip, que suportam integração e entrega contínua. O pipeline permite configurar etapas de validação, testes, entrega em diferentes ambientes (homologação, produção) e aprovações manuais antes da liberação final. Isso garante que o lançamento ocorra de forma segura e eficiente.

### Implantação (Deploy):
A fase de implantação está diretamente relacionada ao lançamento. A implantação é acionada automaticamente pelo pipeline de entrega, que instala e configura o software e a infraestrutura. Ferramentas como o Docker facilitam esse processo, encapsulando o software em contêineres com todas as dependências necessárias para execução. Diferente das máquinas virtuais, o Docker utiliza o sistema operacional do host, o que o torna mais leve e eficiente. Para gerenciar a distribuição desses contêineres em ambientes cloud, ferramentas como Kubernetes e Apache Mesos são amplamente utilizadas, permitindo a orquestração e o escalonamento da infraestrutura.

### Operação:
Após a implantação, a operação do sistema envolve modificações, manutenções e o escalonamento da infraestrutura, conforme a demanda. Ferramentas como Kubernetes e Apache Mesos oferecem funcionalidades avançadas de orquestração, balanceamento de carga (load balancing) e autorrecuperação (self-healing), garantindo que o ambiente continue funcionando de maneira estável e eficiente. Além disso, o Ansible pode ser utilizado para automatizar a gestão de múltiplos servidores, sem a necessidade de agentes instalados nas máquinas, tornando o processo de automação mais leve e ágil.

O escalonamento pode ocorrer de duas formas: vertical ou horizontal. O escalonamento vertical envolve aumentar os recursos de um único host (como memória e processamento), enquanto o escalonamento horizontal adiciona mais hosts para dividir a carga de trabalho. Na arquitetura de microsserviços, o escalonamento horizontal é mais eficiente, pois distribui a carga entre vários contêineres, e os orquestradores como Kubernetes já são projetados para lidar com isso.

### Monitoração:
Embora muitas vezes esquecida, a monitoração é uma fase crucial no ciclo DevOps. Ela permite acompanhar o ambiente em tempo real, analisando o desempenho, comportamento do sistema e dos usuários, e diagnosticando problemas. Ferramentas como Splunk, Datadog e Nagios são usadas para indexar e analisar os logs gerados pelas aplicações e infraestrutura, criando dashboards interativos que consolidam as informações e facilitam o acompanhamento do ambiente. A monitoração contínua ajuda a identificar gargalos de desempenho e a reagir rapidamente a incidentes.

## DEVSECOPS

DevSecOps é uma extensão da cultura DevOps que integra segurança no ciclo de desenvolvimento de software, ao invés de tratá-la como um processo separado ou posterior à implementação. A ideia central do DevSecOps é incorporar práticas de segurança desde o início do desenvolvimento, tornando a segurança uma responsabilidade compartilhada por todas as equipes envolvidas (desenvolvedores, operações e segurança). As vantagens ao se trabalhar com DevSecOps são:

### Objetivos principais do DevSecOps:

* *Automatizar processos de segurança*: Assim como o DevOps automatiza o desenvolvimento e as operações, o DevSecOps promove a automação de testes de segurança, verificações de conformidade e detecção de vulnerabilidades.
* *Incorporar segurança no ciclo de desenvolvimento*: A segurança não deve ser um "gargalo" no final do ciclo. Ferramentas de segurança são integradas ao pipeline de CI/CD (Integração e Entrega Contínua), permitindo testes contínuos à medida que o código é desenvolvido, testado e lançado.
* *Colaboração entre equipes de segurança, desenvolvimento e operações*: Em vez de equipes de segurança isoladas, todos os membros do time têm a responsabilidade de identificar e mitigar vulnerabilidades de forma contínua.

### Principais práticas do DevSecOps:

* Análise de vulnerabilidades em tempo real durante o desenvolvimento, utilizando ferramentas de análise estática de código (SAST) e análise dinâmica de segurança (DAST).
* Testes de segurança automatizados no pipeline de CI/CD.
* Verificação de dependências de terceiros para garantir que bibliotecas e frameworks externos estejam atualizados e sem vulnerabilidades.
* Gestão de patches e atualizações contínuas para lidar com novas vulnerabilidades descobertas.
* Monitoramento e auditoria contínua de ambientes de produção para detectar e responder rapidamente a incidentes de segurança.

### Ferramentas comuns no DevSecOps:

* *Snyk, **SonarQube, **OWASP Dependency-Check* (para verificação de dependências vulneráveis).
* *Aqua Security, **Twistlock* (para proteger contêineres e orquestrações como Kubernetes).
* *HashiCorp Vault, **AWS Secrets Manager* (para gerenciamento seguro de credenciais e dados sensíveis).

