---
title: "Análise de Classes Latentes para Cientistas Sociais"
collection: teaching
type: "Minicurso"
permalink: /oficinas/2024-lca-pet-cs
venue: "PET Ciências Sociais — FAFICH/UFMG"
date: 2024-06-14
location: "Belo Horizonte, Brasil"
---

Minicurso de 6 horas sobre Análise de Classes Latentes (ACL) para pesquisadores
das ciências sociais: como identificar subgrupos qualitativamente distintos numa
população a partir de variáveis que não se observam diretamente.

**Formato:** minicurso em dois encontros, 6 horas
**Público:** graduandos e pós-graduandos em ciências sociais
**Instituição:** PET Ciências Sociais, FAFICH/UFMG (tutoria de Yumi Garcia dos Santos)
**Realização:** 7 e 14 de junho de 2024

A ACL é uma abordagem *centrada na pessoa*: em vez de perguntar como as
variáveis se relacionam entre si na população inteira, pergunta que padrões de
resposta se repetem e que subgrupos eles revelam. É a técnica que usei na
dissertação de mestrado para construir uma tipologia de cientistas brasileiros
segundo suas percepções sobre divulgação científica.

## Programa

**Dia 1 — Fundamentos conceituais**

1. Variáveis latentes, construtos e indicadores; o princípio da independência local
2. Modelos de variável latente: onde a ACL se situa em relação à análise fatorial,
   à TRI e à análise de perfil latente
3. Abordagem centrada nas variáveis × centrada nas pessoas
4. Interpretação dos parâmetros: prevalência (γ) e probabilidade de resposta ao item (ρ)
5. Homogeneidade e separação de classes
6. Seleção do modelo: algoritmo EM, número de classes, AIC e BIC,
   interpretabilidade e parcimônia
7. Diagnósticos de classificação: probabilidade média posterior, entropia e
   chances de correta classificação
8. Nomear as classes — e a falácia do nome

**Dia 2 — Aplicações práticas**

1. ACL com covariáveis: por que a abordagem de três passos está errada e o que
   a estimação em um passo resolve
2. ACL multigrupo: invariância de parâmetros e comparação de prevalências
3. Mãos na massa no RStudio com os pacotes `poLCA` e `glca`
4. Estudo de caso: confiança nas instituições com dados do World Values Survey
5. Preparação dos dados, estimação, leitura das tabelas de ajuste e visualização

## Materiais

- [Slides — dia 1](http://bit.ly/acl_pet_cs)
- [Slides — dia 2](http://bit.ly/acl_pet_cs_2)
- [Código em R usado no estudo de caso (gist)](https://gist.github.com/tbmpereira/1b5b89c60a028be50e156b3d00819a51)

## Referência principal

Collins, L. M.; Lanza, S. T. *Latent class and latent transition analysis: with
applications in the social, behavioral, and health sciences.* Hoboken: Wiley, 2009.
