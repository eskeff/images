---
layout: post
date: 2017-01-25T09:53:21-03:00
title: "Collective Code Ownership - O código é de todos"
author: eskeff
abstract: >
  Collective Code Ownership
---

O que buscamos com a disseminação do conhecimento do código no projeto é justamente evitar situações em que somente um indivíduo é responsável ou “dono” de algum módulo ou tela do sistema. Imagina se esse projeto já está em produção e precisamos fazer um hotfix urgente para o cliente. Vamos dizer que no momento não podemos solucionar por que somente o Fulano sabe como?
Se todos da equipe se sentem confortáveis com o que foi construído facilita e muito a passagem de conhecimento para novos colegas, bem como agilidade para manutenções no código.

# Definição

Basicamente consiste em dividir a responsabilidade com todos do time, ou seja, ninguém é dono de alguma classe, método, tela  ou módulo em específico, todos são responsáveis pela manutenção e em garantir a qualidade do código do projeto.

# Mas como aplicar isso no seu projeto?

Claro que a realidade dos projetos muitas vezes nos impede de atingir o mundo ideal devido custos e tempo do projeto, mas se tivermos as ferramentas e processos para nos auxiliar, o objetivo pode ser atingido.de forma mais eficiente.

 - Utilizar [Code Review](http://cwisoftware.github.io/drops/code-review) é uma das melhores maneiras de espalhar o conhecimento para a equipe.
 - Deixar o código legível e de fácil manutenção como também demonstrado nos Drops [Code Smells](http://cwisoftware.github.io/drops/codesmells-dry-kiss)  e  [Design Patterns](http://cwisoftware.github.io/drops/design-patterns) 
 - Ter uma padrão forte e consistente ajuda o desenvolvedor que precisar alterar outro modulo de seu projeto não se sinta perdido. Podemos usar ferramentas como o [SonarQube](http://cwisoftware.github.io/drops/sonarqube-code-analysis) 
 - Utilizar testes unitários para toda funcionalidade e manutenção do código, para garantir a integridade do projeto e deixar confortavel para que for aplicar a mudança
 - Testes de aceitação automatizados 
 - Fazer uso de [Integração Contínua](http://cwisoftware.github.io/drops/maturidade-integracao-continua) que executa esses testes a cada nova mudança.


