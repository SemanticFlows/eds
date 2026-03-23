# Resumo preparatório para reunião da plataforma EDS

## Leitura geral do material

A pasta `eds` não contém uma base de código da plataforma até o momento. O conteúdo atual é de definição de produto, UX e conceito.

Materiais analisados:

- `Briefing de Features da Plataforma.md`
- `Explicação expandida - Aplicação.md`
- `PRD Ia engineering.md`
- Figma `Hacka eds`
- Figma `DESAFIO - 1`

## Síntese executiva

A proposta da plataforma EDS é uma experiência **mobile-first** centrada em **apostas ao vivo guiadas por placar e contexto de jogo**, combinada com uma camada forte de **gamificação**, **carteira visual lúdica**, **socialização por torcida** e um **avatar assistivo com IA** como principal diferencial de marca e experiência.

Em termos de posicionamento, o produto tenta sair do padrão de casa de aposta tradicional e se aproximar de uma experiência híbrida entre:

- betting em tempo real
- interface de game/mobile app
- sistema de progressão e retenção
- assistência contextual por IA

## O que já está claro no conceito

### 1. Core do produto

O núcleo é uma plataforma de apostas com foco em:

- jogos e eventos ao vivo
- placar como eixo da tomada de decisão
- odds dinâmicas
- leitura contínua de contexto de partida

Há também expansão para:

- pré-jogo
- mercados específicos
- cassino e jogos integrados

### 2. Estrutura de navegação

A navegação proposta é mobile-first, baseada em tabs inferiores:

- Jogos
- Buscar
- Torcida
- Carteira
- Conta

O padrão visual recorrente é:

- cards modulares
- blocos retangulares que podem expandir
- destaque para áreas centrais quadradas e interativas
- feedback visual contínuo

### 3. Diferenciais de UX

Os diferenciais mais marcantes descritos no material são:

- placar como elemento hero da interface
- visualização animada de intensidade de jogo
- carteira com saldo e apostas ativas em formato de órbitas
- camada social de "torcida" baseada em comportamento coletivo
- avatar assistivo que aprende com o padrão do usuário

### 4. Camada de retenção

O conceito está fortemente apoiado em mecanismos de engajamento:

- missões
- loja interna
- progressão por rank
- recompensas diárias
- torneios
- promoções

Isso indica que a plataforma não está sendo pensada só como operação transacional de aposta, mas como ecossistema recorrente.

## Leitura do direcionamento visual

Mesmo sem acesso detalhado aos frames dos Figmas via automação, os documentos locais e os metadados públicos indicam aderência entre conceito e direção visual.

Leitura inferida a partir do material:

- `Hacka eds` parece concentrar o conceito-base da experiência e da navegação principal.
- `DESAFIO - 1` aparenta ser uma evolução ou refinamento do desafio visual/produto, com atualização mais recente.

Sinais concretos identificados nos links públicos:

- `Hacka eds` publicado em 20 de março de 2026 e modificado em 21 de março de 2026
- `DESAFIO - 1` publicado em 21 de março de 2026 e modificado em 23 de março de 2026

## Hipótese de proposta de valor

Se formos resumir a proposta em uma frase para a reunião:

> A EDS quer transformar apostas ao vivo em uma experiência mais visual, assistida e gamificada, com cara de produto mobile nativo e identidade própria.

## Principais forças do conceito

### Forças estratégicas

- Diferenciação clara frente a interfaces genéricas de betting
- Potencial de marca muito forte com o avatar
- Boa combinação entre operação, retenção e identidade visual
- Estrutura modular que pode crescer por fases

### Forças de experiência

- foco em ação rápida
- feedback imediato
- leitura de contexto em tempo real
- interface com potencial alto de memorabilidade

## Principais riscos e pontos de atenção

### 1. Escopo muito amplo para fase inicial

Hoje o conceito mistura, ao mesmo tempo:

- betting ao vivo
- pré-jogo
- cassino
- carteira avançada
- social
- missões
- loja
- progressão
- promoções
- avatar com IA

Para MVP, isso é grande demais. A reunião precisa definir o que entra primeiro.

### 2. Complexidade de implementação do avatar

O avatar é um grande diferencial, mas também é uma das peças mais complexas porque envolve:

- instrumentação comportamental
- modelo de perfil do usuário
- regras de intervenção
- UX de confiança e controle
- cuidado regulatório para não parecer automação indevida de aposta

### 3. Risco de excesso de estímulo visual

Como a proposta visual é intensa, há um risco real de:

- sobrecarga cognitiva
- perda de legibilidade
- confusão entre informação crítica e elemento decorativo

Na prática, a qualidade do produto vai depender muito da hierarquia visual final.

### 4. Dependências regulatórias e de compliance

Como o produto envolve aposta, promoções, IA assistiva e retenção, a camada de compliance deve entrar cedo na conversa.

Especial atenção para:

- transparência de odds e sugestões
- limites de incentivo
- linguagem do avatar
- responsabilidade sobre recomendações contextuais

## Recomendações para conduzir a reunião

### Pergunta central

O que exatamente a EDS quer validar primeiro: **motor de aposta ao vivo**, **experiência visual diferenciada** ou **assistência por IA**?

### Decisões que valem sair da reunião

1. Definir o recorte do MVP
2. Escolher o principal diferencial da primeira versão
3. Separar o que é feature núcleo do que é camada de retenção
4. Confirmar se o avatar entra no MVP ou em fase 2
5. Validar o fluxo principal de navegação mobile

## Sugestão de recorte de MVP

Um recorte viável, coerente com o material, seria:

- home de jogos ao vivo
- detalhe de jogo com odds/contexto
- carteira básica
- conta
- uma mecânica simples de retenção

Fase seguinte:

- torcida/social
- missões e progressão
- promoções estruturadas
- avatar assistivo com memória de comportamento

## Perguntas úteis para levar

- Qual problema principal estamos resolvendo melhor do que uma casa de aposta comum?
- O avatar é diferencial de marca ou funcionalidade central do produto?
- O que precisa ser demonstrável em protótipo e o que precisa ser operacional de verdade?
- O cassino faz parte da proposta inicial ou apenas da visão futura?
- Quais sinais definem sucesso do MVP: retenção, conversão, frequência, ticket, tempo de sessão?
- Que partes da experiência exigem validação jurídica/compliance antes de avançar?

## Situação atual do repositório

O repositório está em estágio de documentação/conceituação. Não foi encontrada implementação funcional da plataforma nesta pasta.

Arquivos centrais:

- `Briefing de Features da Plataforma.md`: visão macro das features e arquitetura de UX
- `Explicação expandida - Aplicação.md`: detalhamento da experiência mobile, navegação e componentes
- `PRD Ia engineering.md`: definição do avatar assistivo e do comportamento adaptativo

## Resumo final para abertura de reunião

Hoje a EDS está bem definida como visão de produto: uma plataforma de apostas ao vivo mobile-first, gamificada, com forte apelo visual e potencial de diferenciação por IA assistiva. O ponto principal da reunião deve ser transformar essa visão em recorte executável, priorizando o que é núcleo de valor no MVP e o que fica como camada evolutiva.
