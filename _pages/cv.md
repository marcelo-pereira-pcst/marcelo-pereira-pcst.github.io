---
layout: archive
title: "Currículo"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!--
  VERSÃO 3 — acrescenta o título da tese, o detalhamento do estágio em Oviedo
  (coorientador e grupo de pesquisa) e a Análise de Classes Latentes entre as
  competências técnicas. A seção "Oficinas e minicursos" agora se alimenta
  sozinha das duas atividades cadastradas em _teaching.

  Continuam valendo as correções da versão anterior: seções em `------` (h2)
  em vez de `======` (h1), e título "Currículo" para bater com o menu.
-->

Formação
------
* **Doutorado em Sociologia (em andamento)**, Universidade Federal de Minas Gerais (UFMG), 2024 – presente
  * Tese: *Integração subordinada e divulgação científica: tipologias de engajamento no espaço lusófono*
  * Orientador: Yurij Castelfranchi
  * Co-orientador: Carmelo Polino
* **Mestrado em Sociologia**, Universidade Federal de Minas Gerais (UFMG), 2023
  * Dissertação: *Ciência, sociedade, divulgação científica: a visão dos cientistas*
* **Master 1 em Estudos Latino-americanos**, Université Sorbonne Nouvelle – Paris 3, 2015
* **Graduação em Secretariado Executivo Trilíngue**, Universidade Federal de Viçosa, 2006

Estágio de pesquisa no exterior
------
* **Universidad de Oviedo** (Espanha), setembro de 2026 – maio de 2027
  * Estágio doutoral no grupo de pesquisa CTS (Ciencia, Tecnología y Sociedad)
  * Coorientação: Prof. Dr. Carmelo Polino
  * Validação do instrumento de coleta, desenho amostral e plano de análise do survey comparativo da tese
  <!-- Se a bolsa PDSE/CAPES estiver confirmada, acrescente aqui uma linha:
       * Bolsa PDSE/CAPES -->

Experiência profissional
------
* **Diretoria de Divulgação Científica (DDC) – UFMG**, 2016 – presente
  * Cargo: Secretário Executivo
  * Atuação na gestão de políticas de comunicação pública da ciência e tecnologia

Habilidades e competências
------
* **Domínios de pesquisa:**
  * Sociologia da Ciência e Estudos Sociais das Ciências e das Tecnologias
  * Comunicação Pública da Ciência e percepção pública de C&T
  * Métodos digitais e sociologia computacional
* **Competências técnicas:**
  * **Análise de dados** — ciência de dados aplicada às ciências sociais, com domínio de Python e R
  * **Métodos quantitativos** — desenho e análise de surveys, Análise de Classes Latentes, análise fatorial e regressão logística
  * **Gestão de dados** — modelagem e extração com **SQL** e técnicas de *web scraping*
  * **Infraestrutura** — administração de sistemas **Linux** (Debian/Ubuntu) e orquestração de containers com **Docker** para ambientes de pesquisa
* **Idiomas:**
  * Português (nativo)
  * Inglês (avançado)
  * Francês (avançado)
  * Espanhol (intermediário)

Publicações
------
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Participação em eventos e palestras
------
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Oficinas e minicursos ministrados
------
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Ver a [descrição das oficinas oferecidas](/oficinas/).

Grupos de pesquisa e laboratórios
------
* Observatório InCiTe – Inovação, Cidadania e Tecnociência (UFMG)
* Instituto Nacional de Ciência e Tecnologia em Comunicação Pública da Ciência e Tecnologia – [INCT-CPCT](https://inct-cpct.fiocruz.br/)
* Grupo CTS – Ciencia, Tecnología y Sociedad, Universidad de Oviedo (2026–2027)

<br>

🌐 **English version:** [this CV in English](/cv-en/).
