# System Design e/ou Arquitetura de Sistemas

## Porque fazemos sistemas ?
A ideia principal é que um Design de Sistema ou Arquitetura **atenda as necessidades** de uma empresa/organização por meio de sistemas **COERENTES** e **EFICIENTES**

## Como criamos sistemas que resolvem problemas de forma coerente e eficiente ?

_Um bom projeto de sistema exige que os engenheiros pensem em tudo em uma infraestrutura, desde o hardware/software até os dados e como eles são armazenados._

**É possível que engenheiros pensem em tudo ? 👀**

Acredito que quando falamos de System Design estamos falando também de times multidisciplinares por isso, antes de mais nada, busque entender o problema e como o ambiente em que você está inserida(o), consegue ajudar técnicamente para buscar especialistas nas decisões que precisam ser tomadas.

## Projetos de Arquiterura são baseados em decisões coletivas.

**Porque o ambiente é importante quando falamos em System Desgin ?**

Não adianta escolhermos um banco documental em uma empresa onde não temos conhecimento técnico para manter tal banco. Se o time de Persistência não está pronto para lhe dar o suporte necessário para atuar com determinado banco e você ficará cego em observabilidade, disponibilidade e gerencia do banco de dados, é melhor ir para a zona de conforto do que determinando ambiente técnico te entrega ou propor esperar e/ou contribuir para que a companhia em algum momento alcance o ní
vel de maturidade técnica que aquele problema de arquitetura precisa.

## Princípios de Design de Sistemas

**KISS - Keep it simple and stupid**

Mantenha o mais simples possível para resolver os problemas do **HOJE**.
Não adicionar complexidade desnecessária para resolver problemas hipotéticos que possamos enfrentar em um futuro distante. 
Pensar no futuro é fantástico, MAS não dá pra assumir o ônus de planejar eventualidades que podem nem acontecer, cuidado para não cair na paralisia do planejamento.


## Provavelmente você já ouviu falar em Alta coesão e baixo desacoplamento.


**Separe responsabilidades**
- Alta coesão está muito ligado ao princípio da responsabilidade única.
Um objeto é coeso quando faz exatamente o que se propõe, sem ir além disso.

Para exemplificar

Responsabilidade: Dever de responder pelo próprio comportamento.

Quando segregamos responsabilidades, naturalmente simplificamos nossos serviços, funções e componentes. Simplificar implica em usar menos esforço cognitivo para manutenção, menos complexidade para mudanças e consequentemente menor possibilidade de novos bugs surgirem com a evolução do código.


**Pense em desacoplamento**

Em aspecto global acoplamento é o grau de dependência entre dois "artefatos". Onde artefatos podem ser entidades, métodos, componente, tabelas, sistemas e por ai vai.

O baixo acoplamento é frequentemente um sinal de um sistema de computador bem estruturado e de um bom design, e quando combinado com alta coesão, suporta os objetivos gerais de alta **legibilidade** e **facilidade de manutenção**.

https://aws.amazon.com/pt/microservices/



**Se preocupe com escala**

Na concepção do desenho da solução, na modelagem de dados, na entrega de cada componente da arquitetura.

- Ferramentas de teste de carga
  - Apache Banchmark : https://www.tutorialspoint.com/apache_bench/apache_bench_quick_guide.htm
  - K6 : https://k6.io/
  - Predator : https://zooz.github.io/predator/myfirsttest.html

**Escolha bem a onde e como vai armazenar deus dados**


...


**Processo de desenvolvimento da Arquitetura**

1. CODEBASE = “Código fonte gerenciado por um controle de revisão e diversos ‘deploys’.”
2. DEPENDENCIAS = “Declarar e isolar dependências explicitamente.”
3. CONFIGURAÇÃO = “Armazenar a configuração no ambiente”.
4. BACKING SERVICES = “Tratar serviços de apoio como recursos anexos”.
5. BUILD, RELEASE AND RUN = “Separar completamente etapas de construção e execução”.
6. CONCORRÊNCIA = “Dimensionar a aplicação através de um modelo de processo”
7. DISPONIBILIDADE = “Tornar o sistema mais robusto com inicialização rápida e finalização elegante”.
8. PARIDADE DE AMBIENTES = “Manter os ambientes de desenvolvimento, testes e produção mais parecidos possíveis”.
9. OBSERVABILIDADE = “Logs, Métricas e Traces/Tracking”.


**Custo**

- Quais são os principais elementos ou objetos do sistema?
- Como os elementos estão conectados? Quais são as relações? Quais são suas entradas e saídas?
- Qual objetivo isso alcança?
- O que para além do objetivo conseguimos abstrair dessa arquitetura ? ++

Refs.
- https://github.com/karanpratapsingh/system-design
- https://www.intercom.com/blog/six-principles-of-system-design/
- https://roadmap.sh/software-design-architecture
- http://blog.askm.com.br/2019/02/12/metodologia-dos-12-fatores/
