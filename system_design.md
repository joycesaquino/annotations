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

**Separe responsabilidades**

**Pense em desacoplamento**

**Se preocupe com escala**

**Escolha bem a forma como vai armazenar deus dados**

**Observabilidade, Monitoria e Tracking**

**Processo de desenvolvimento da Arquitetura**

**Custo**

- Quais são os principais elementos ou objetos do sistema?
- Como os elementos estão conectados? Quais são as relações? Quais são suas entradas e saídas?
- Qual objetivo isso alcança?
- O que para além do objetivo conseguimos abstrair dessa arquitetura ? ++

