# Desafio criativo: agente de atendimento ZeroCell

**Origem:** Bootcamp Bradesco — IA do Zero à Prática, da DIO  
**Tema:** engenharia de prompt e IA generativa  
**Contexto:** atendimento ao cliente de uma operadora fictícia de telefonia móvel  
**Canal previsto:** WhatsApp

## Sobre o desafio

O objetivo é elaborar um prompt para orientar um agente de IA que conversa com pessoas interessadas em contratar um plano, mas que ainda têm dúvidas ou receios. O agente deve ser claro, objetivo e útil durante a decisão, sem recorrer a informações inventadas ou insistir de forma inadequada na contratação.

## O que o agente deve fazer

1. Consultar os planos disponíveis para o cliente com base em sua localização.
2. Comparar as opções e explicar as condições relevantes de cada plano.
3. Orientar o cliente, passo a passo, sobre como avançar com a contratação.
4. Esclarecer dúvidas e solicitar informações adicionais quando necessário para responder com segurança.

## Regras definidas no prompt

- Usar linguagem simples, animada e semiformal, com respostas de no máximo sete linhas.
- Organizar etapas em listas ordenadas e enumerar os planos apresentados.
- Nunca solicitar CPF ou RG.
- Não inventar preços, planos, cobertura ou outras informações não comprovadas.
- Quando não tiver acesso a uma informação, deixar isso claro e indicar o site oficial para consulta.
- Encaminhar para atendimento humano quando o cliente quiser contratar ou estiver insatisfeito com o chatbot.
- Ao encaminhar, informar o motivo e resumir o que já foi registrado na conversa.

## Decisões importantes

O prompt precisa equilibrar o objetivo comercial com a precisão das informações e a experiência do cliente. A orientação para aproveitar uma oferta rapidamente só deve ser usada quando houver uma condição real e verificável que justifique a urgência. Caso contrário, o agente não deve criar escassez nem pressionar o cliente com alegações sem comprovação.

Também existe uma dependência importante: para consultar planos por localização, comparar condições e encaminhar uma contratação de verdade, o agente precisaria de acesso a fontes confiáveis e atualizadas, além das integrações necessárias. O prompt define o comportamento esperado, mas não fornece esses recursos por si só.

## Arquivo original

O prompt original permanece no repositório, sem ser reproduzido ou alterado por esta documentação. [Acesse a pasta do desafio no GitHub](https://github.com/andrewgadelha/meus-desafios-criativos/tree/main/desafios) para abrir o arquivo existente.

## Navegação

- [Voltar ao README principal do repositório](../README.md)
- [Abrir a pasta `desafios` no GitHub](./)
