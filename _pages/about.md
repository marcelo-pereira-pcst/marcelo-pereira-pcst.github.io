---
layout: archive
title: "Marcelo Pereira"
permalink: /
author_profile: true
lang: pt-BR
excerpt: "Pesquiso como cientistas de países de língua portuguesa entendem — e praticam — a divulgação científica."
---

{% include idiomas.html %}

<!--
  VERSÃO 3 — as linhas de trabalho agora refletem a tese de fato (o recorte
  lusófono e a geopolítica do conhecimento), e não mais a descrição genérica
  que estava no site. O bloco sobre Oviedo traz o coorientador e o objetivo
  do estágio, e — conforme pedido — não menciona oficinas.
-->

Como os cientistas de países de língua portuguesa entendem — e praticam — a
divulgação científica?

Essa é a pergunta que organiza meu trabalho. Sou doutorando em Sociologia na
**UFMG** (PPGS/FAFICH), sob orientação do Prof. Yurij Castelfranchi, e secretário
executivo da Diretoria de Divulgação Científica da universidade desde 2016 —
o que significa que estudo, de dentro, uma prática que ajudo a fazer acontecer.

> **De setembro de 2026 a maio de 2027 realizo estágio doutoral na Universidad
> de Oviedo**, sob coorientação do Prof. Dr. Carmelo Polino, no grupo CTS
> (Ciencia, Tecnología y Sociedad), para o desenho e a validação do survey
> comparativo da tese. [Mais sobre a pesquisa](/pesquisa/).

## Linhas de trabalho

**Cientistas e divulgação científica.** Percepções, disposições e obstáculos
declarados por pesquisadores — o que os leva a divulgar, e o que os impede.
A dissertação de mestrado tratou do caso brasileiro e deu origem a uma
[proposta de classificação](/publications/) desses perfis.

**Ciência periférica e geopolítica do conhecimento.** Como a posição de um
sistema científico na divisão internacional do trabalho científico molda o que
seus pesquisadores consideram digno de ser comunicado — e em que língua.

**O espaço lusófono como caso.** Brasil, Portugal e países africanos de língua
oficial portuguesa: sistemas que compartilham um idioma e heranças coloniais,
mas quase nada de suas condições materiais de pesquisa. É o recorte da tese
em andamento.

**Métodos.** Sociologia computacional e análise quantitativa aplicada às
ciências sociais — surveys comparativos, modelos de classes latentes, R e Python.

## Em destaque

{% assign destaque = site.portfolio | sort: 'date' | reverse | first %}
{% if destaque %}
[**{{ destaque.title }}**]({{ destaque.url | relative_url }}) — {{ destaque.excerpt | strip_html | strip_newlines | truncate: 200 }}
{% endif %}

## Novidades

{% assign recentes = site.posts | slice: 0, 3 %}
{% if recentes.size > 0 %}
{% for post in recentes %}
- **{{ post.date | date: "%b %Y" }}** — [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

[Ver todas as novidades →](/year-archive/)
{% endif %}

---

Escrevo, apresento e colaboro em português, espanhol, inglês e francês.
Contato: [mapereira@ufmg.br](mailto:mapereira@ufmg.br) ·
[currículo](/cv/) ·
[oficinas e minicursos](/oficinas/) ·
[this page in English](/about-en/)
