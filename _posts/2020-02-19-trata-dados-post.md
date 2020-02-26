---
layout: post
published: false
title: Tratamento de dados com R
subtitle: Um pequeno projeto em R que realizei para pre processamento de dados para Linkage de dados utilizando o LinkPlus.
---

### Tratando dados com R


Neste artigo vou apresentar um pequeno projeto que fiz utilizando a linguagem de programação R. O objetivo do script criado é realizar um pré processamento de dados para que esses dados possam ser 'linkados' utilizando o LinkPLus [Link PLus](https://www.cdc.gov/cancer/npcr/tools/registryplus/lp.htm).

O link Plus é um software desenvolvido pelo Centers Of Disease Control and Prevention - CDC. o CDC é o centro de controle de Doenças dos Estados Unidos, orgão responsável por avaliar e garantir a saúde do povo américano, em uma comparação seria semelhante à Secretaria de Vigilância em Saúde - SVS aqui no Brasil.

O Link Plus é um software de relacionamento probabilistico de registros de banco de dados (linkage), o link plus pode identificar registros presentes em um banco de dados que também estão presentes em outro banco de dados, alem disso também é capaz de identificar registros duplicados em determinado banco de dados. O Link Plus por si só merece um post completo, vai ficar na todo list para uma  proxima postagem

A pedido de uma colega de trabalho que iria ministrar um minicurso de linkage de base de dados, fiz um script em R para preparar os dados para a atividade.

O escopo foi o seguinte: 


`code`
