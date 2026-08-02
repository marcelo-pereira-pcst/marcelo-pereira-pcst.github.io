---
layout: archive
title: "Marcelo Pereira"
permalink: /about-es/
author_profile: true
lang: es
excerpt: "Investigo cómo los científicos de los países de lengua portuguesa entienden — y practican — la divulgación científica."
---

{% include idiomas.html %}

<!--
  Versión en español de la página inicial.

  Nota terminológica: uso "divulgación científica" como término general y
  "comunicación pública de la ciencia" cuando el registro es más técnico —
  que es el uso corriente en la literatura iberoamericana del área. Si en
  Oviedo el término dominante resulta ser "cultura científica", vale ajustar.

  El campo `lang: es` del front matter sólo surte efecto después del pequeño
  ajuste en _layouts/default.html descrito en el LEIA-ME.
-->

¿Cómo entienden —y practican— la divulgación científica los investigadores de
los países de lengua portuguesa?

Esa es la pregunta que organiza mi trabajo. Soy doctorando en Sociología en la
**Universidade Federal de Minas Gerais** (PPGS/FAFICH, Brasil), bajo la
dirección del Prof. Yurij Castelfranchi, y secretario ejecutivo de la Dirección
de Divulgación Científica de la universidad desde 2016 — lo que significa que
estudio, desde dentro, una práctica que ayudo a que ocurra.

> **De septiembre de 2026 a mayo de 2027 realizo una estancia doctoral en la
> Universidad de Oviedo**, bajo la codirección del Prof. Carmelo Polino, en el
> grupo CTS (Ciencia, Tecnología y Sociedad), dedicada al diseño y la validación
> de la encuesta comparativa que sostiene la tesis.
> [Más sobre la investigación](/pesquisa/).

## Líneas de trabajo

**Científicos y divulgación científica.** Percepciones, disposiciones y
obstáculos declarados por los investigadores: qué los lleva a divulgar y qué se
lo impide. Mi tesis de maestría abordó el caso brasileño y dio lugar a una
[propuesta de clasificación](/publications/) de estos perfiles.

**Ciencia periférica y geopolítica del conocimiento.** Cómo la posición de un
sistema científico en la división internacional del trabajo científico moldea lo
que sus investigadores consideran digno de ser comunicado — y en qué lengua.

**El espacio lusófono como caso.** Brasil, Portugal y los países africanos de
lengua oficial portuguesa comparten un idioma y herencias coloniales, pero casi
ninguna de sus condiciones materiales de investigación. Es el recorte de la
tesis en curso.

**Métodos.** Sociología computacional y análisis cuantitativo aplicado a las
ciencias sociales: encuestas comparativas, modelos de clases latentes, R y Python.

## Destacado

{% assign destaque = site.portfolio | sort: 'date' | reverse | first %}
{% if destaque %}
[**{{ destaque.title }}**]({{ destaque.url | relative_url }}) — {{ destaque.excerpt | strip_html | strip_newlines | truncate: 200 }}
{% endif %}

---

Escribo, presento y colaboro en portugués, español, inglés y francés.
Contacto: [mapereira@ufmg.br](mailto:mapereira@ufmg.br) ·
[currículum](/cv/) ·
[talleres y cursos breves](/oficinas/)
