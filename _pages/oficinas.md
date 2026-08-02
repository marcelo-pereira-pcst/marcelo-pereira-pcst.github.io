---
layout: archive
title: "Oficinas e minicursos"
permalink: /oficinas/
author_profile: true
excerpt: "Formação em divulgação científica e em métodos quantitativos para as ciências sociais."
---

{% include base_path %}

<!--
  VERSÃO 2 — o catálogo agora sai das duas oficinas que você de fato já
  ministrou, em vez dos temas hipotéticos da versão anterior. É mais forte
  assim: cada item do catálogo tem uma página de "já realizada" atrás dele.

  Sobre a disponibilidade durante o período em Oviedo: mantive aqui, porque
  esta é a página de oficinas. Retirei a menção às oficinas das seções sobre
  o sanduíche (home, /pesquisa/, versão em inglês e post), como você pediu.
  Se quiser tirar daqui também, é só apagar o parágrafo marcado abaixo.
-->

Ofereço oficinas e minicursos em duas frentes: **divulgação científica** — o que
é, o que não é, e como as instituições a organizam — e **métodos quantitativos
para as ciências sociais**, com ênfase em modelos de classes latentes. A
abordagem vem de dois lugares ao mesmo tempo: a pesquisa sociológica sobre como
cientistas percebem a divulgação e a prática cotidiana na Diretoria de
Divulgação Científica da UFMG desde 2016.

<!-- [DISPONIBILIDADE — apague este parágrafo se preferir] -->
Estou na Europa entre setembro de 2026 e maio de 2027 e tenho disponibilidade
para oferecer estas atividades em universidades e centros de pesquisa.
Português, espanhol, inglês e francês.

Para convites: [mapereira@ufmg.br](mailto:mapereira@ufmg.br)

## O que ofereço

### O que eu faço ou pretendo fazer é divulgação científica?
*Oficina · servidores, docentes e equipes de comunicação institucional*

A fronteira — nem sempre óbvia — entre extensão universitária, comunicação
institucional e divulgação científica. Percorre os modelos de déficit, diálogo e
engajamento, a crítica latino-americana ao próprio termo "extensão" e o modo
como uma universidade institucionaliza (ou não) sua política de divulgação. Os
participantes saem sabendo situar a própria atividade nesse mapa.

Ministrada em três edições (2023, 2024 e 2025) no curso *Extensão Acadêmica na
Prática*, da Pró-Reitoria de Extensão da UFMG.
[Ver programa completo](/oficinas/extensao-academica-na-pratica).

### Análise de Classes Latentes para cientistas sociais
*Minicurso · 6 a 12 horas · pós-graduandos e pesquisadores*

Como identificar subgrupos qualitativamente distintos numa população a partir de
variáveis que não se observam diretamente. Vai dos fundamentos conceituais —
independência local, prevalência, probabilidade de resposta ao item, critérios
de ajuste — até a estimação prática no R com `poLCA` e `glca`, incluindo
covariáveis e modelos multigrupo. Cada participante roda um caso completo.

Ministrado em 2024 no PET Ciências Sociais da FAFICH/UFMG.
[Ver programa completo](/oficinas/2024-lca-pet-cs).

## Realizadas

{% assign realizadas = site.teaching | sort: 'date' | reverse %}
{% if realizadas.size > 0 %}
  <ul>
  {% for post in realizadas %}
    {% include archive-single.html %}
  {% endfor %}
  </ul>
{% else %}
*Em breve.*
{% endif %}
