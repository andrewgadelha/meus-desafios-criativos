# Meus Desafios Criativos

Uma coleção de desafios e experimentos com modelos de linguagem (LLMs), com foco em criar prompts para situações práticas. A ideia é explorar como contexto, instruções, regras e limites bem definidos ajudam a orientar as respostas de uma IA.

Este repositório reúne os prompts e a documentação de cada desafio. O foco não é apenas escrever uma instrução, mas deixar claro qual problema ela procura resolver e quais cuidados são necessários para usá-la com responsabilidade.

## Desafio em destaque

### Agente de atendimento da ZeroCell

Exercício de engenharia de prompt para estruturar um agente de atendimento de uma operadora fictícia de telefonia móvel, com atuação prevista no WhatsApp. O agente deve esclarecer dúvidas de clientes cautelosos, apresentar opções de planos com base em informações verificadas e orientar os próximos passos da contratação.

- [**Ler a documentação do desafio**](./desafios/README-desafio-zerocell.md)
- [**Acessar a pasta com o prompt original**](./desafios/)

## Como os desafios são abordados

Os prompts são estruturados considerando:

- **Contexto e papel:** quem é o agente, quem ele atende e em qual situação.
- **Objetivo e tarefas:** o que a IA deve resolver em cada interação.
- **Tom e formato:** como organizar a resposta para torná-la clara e adequada ao canal.
- **Regras e limites:** o que não pode ser solicitado, afirmado ou inventado.
- **Dúvidas e encaminhamento:** quando pedir esclarecimentos ou direcionar o caso para atendimento humano.

## Próximos desafios

Novos prompts poderão ser adicionados conforme eu explorar outros problemas e aplicações de IA generativa. A documentação de cada exercício registra seu contexto, seus objetivos e os principais critérios definidos no prompt.

## Observação

Um prompt, por si só, não implementa nem conecta um agente a sistemas reais. Consultas a dados atualizados, integrações com plataformas e transferência para atendimento humano dependem de ferramentas e serviços adicionais. Quando um exemplo exigir dados externos, eles devem ser verificados — não presumidos pelo modelo.
