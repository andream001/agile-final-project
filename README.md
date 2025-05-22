# Projeto Final Agile - Catálogo de Produtos

## Visão Geral

Este repositório contém o projeto final do curso de metodologia ágil do Coursera. O projeto consiste em um catálogo de produtos de back-end para um site de e-commerce, desenvolvido seguindo os princípios da metodologia ágil e utilizando o GitHub como ferramenta de gestão.

## Objetivo do Projeto

O objetivo deste projeto é aplicar os conceitos e práticas da metodologia ágil aprendidos durante o curso, incluindo:

- Criação e gerenciamento de histórias de usuário
- Configuração e utilização de um quadro Kanban
- Priorização e estimativa de histórias
- Planejamento e execução de sprints
- Acompanhamento do progresso através de gráficos de burndown

## Estrutura do Quadro Kanban

O quadro Kanban para este projeto é composto por seis colunas principais:

1. **Icebox**: Histórias identificadas, mas não priorizadas para o momento
2. **Product Backlog**: Lista priorizada de histórias de usuário para sprints futuros
3. **Sprint Backlog**: Histórias selecionadas e comprometidas para o sprint atual
4. **In Progress**: Histórias que estão sendo ativamente trabalhadas
5. **Review/QA**: Histórias desenvolvidas que estão passando por revisão e testes
6. **Done**: Histórias concluídas que atendem a todos os critérios de aceitação

## Histórias de Usuário

O projeto inclui 10 histórias de usuário, seguindo o formato "Como... Eu preciso... De forma que..." e com critérios de aceitação no formato Gherkin "Given... When... Then...":

1. Capacidade de criar um produto no catálogo
2. Capacidade de recuperar um produto do catálogo
3. Capacidade de atualizar um produto no catálogo
4. Capacidade de excluir um produto do catálogo
5. Capacidade de listar todos os produtos do catálogo
6. Capacidade de consultar um subconjunto de produtos no catálogo
7. Capacidade de curtir um produto no catálogo
8. Capacidade de não gostar de um produto no catálogo
9. Hospedagem na nuvem (Dívida Técnica)
10. Automação para implantar novas alterações na nuvem (Dívida Técnica)

## Rótulos e Priorização

As histórias foram classificadas com os seguintes rótulos:

- **high priority**: Histórias 1, 2, 5
- **medium priority**: Histórias 3, 4, 6
- **low priority**: Histórias 7, 8, 9, 10
- **technical debt**: Histórias 9, 10

## Estimativas

As histórias foram estimadas usando a escala de pontos de história:

- Histórias simples (2-3 pontos): #2, #4, #5, #7, #8
- Histórias médias (5 pontos): #1, #3
- Histórias complexas (8-13 pontos): #6, #9, #10

## Sprint 1

O primeiro sprint do projeto, denominado "Sprint 1 - Funcionalidades Básicas do CRUD", inclui as 5 histórias principais:

1. Capacidade de criar um produto no catálogo (5 pontos)
2. Capacidade de recuperar um produto no catálogo (3 pontos)
3. Capacidade de atualizar um produto no catálogo (5 pontos)
4. Capacidade de excluir um produto no catálogo (3 pontos)
5. Capacidade de listar todos os produtos do catálogo (3 pontos)

Total de pontos para o Sprint 1: 19 pontos

## Documentação Adicional

Para uma documentação mais detalhada do projeto, consulte o arquivo [kanban_documentation.md](kanban_documentation.md), que contém:

- Descrição completa de todas as histórias de usuário
- Critérios de aceitação detalhados
- Simulação do progresso do sprint
- Gráfico de burndown
- Explicação da organização do quadro Kanban

## Como Usar Este Repositório

1. Explore as histórias de usuário na aba "Issues"
2. Visualize o quadro Kanban na aba "Projects"
3. Acompanhe o progresso do sprint através do milestone "Sprint 1"
4. Consulte a documentação detalhada no arquivo [kanban_documentation.md](kanban_documentation.md)

## Tecnologias Utilizadas

- GitHub Issues para gerenciamento de histórias de usuário
- GitHub Projects para o quadro Kanban
- GitHub Milestones para o planejamento de sprints

## Autor

Este projeto foi desenvolvido por André Luiz Bunhak como parte do projeto final do curso de metodologia ágil do Coursera.
