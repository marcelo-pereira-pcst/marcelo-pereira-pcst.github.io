---
layout: archive
title: "Marcelo Pereira"
permalink: /about-fr/
author_profile: true
lang: fr
excerpt: "J'étudie la manière dont les chercheurs des pays lusophones conçoivent — et pratiquent — la vulgarisation scientifique."
---

{% include idiomas.html %}

<!--
  Version française de la page d'accueil.

  Note terminologique : « vulgarisation scientifique » est le terme courant en
  français, mais il porte une connotation descendante (du savant vers le
  profane) que la littérature dialogique conteste — c'est précisément l'objet
  de votre recherche. J'emploie « vulgarisation » comme terme général et
  « communication publique des sciences » lorsque le registre est plus
  technique. En contexte québécois, « médiation scientifique » serait plus
  usuel.

  Typographie : les espaces insécables avant « ? » et « : » sont écrites
  &nbsp; pour éviter qu'un point d'interrogation se retrouve seul en début
  de ligne.

  Le champ `lang: fr` du front matter ne prend effet qu'après le petit
  ajustement de _layouts/default.html décrit dans le LEIA-ME.
-->

Comment les chercheurs des pays lusophones conçoivent-ils — et pratiquent-ils —
la vulgarisation scientifique&nbsp;?

C'est la question qui organise mon travail. Je suis doctorant en sociologie à
l'**Universidade Federal de Minas Gerais** (PPGS/FAFICH, Brésil), sous la
direction du Prof. Yurij Castelfranchi, et secrétaire exécutif de la Direction
de la vulgarisation scientifique de l'université depuis 2016 — ce qui signifie
que j'étudie de l'intérieur une pratique que je contribue à faire exister.

> **De septembre 2026 à mai 2027, j'effectue un séjour doctoral à l'Universidad
> de Oviedo** (Espagne), sous la codirection du Prof. Carmelo Polino, au sein du
> groupe CTS (Sciences, Technologie et Société), consacré à la conception et à
> la validation de l'enquête comparative au cœur de ma thèse.
> [En savoir plus sur la recherche](/pesquisa/).

## Axes de recherche

**Les chercheurs et la vulgarisation scientifique.** Perceptions, dispositions
et obstacles déclarés par les chercheurs&nbsp;: ce qui les pousse à vulgariser,
et ce qui les en empêche. Mon mémoire de master portait sur le cas brésilien et
a donné lieu à une [proposition de classification](/publications/) de ces profils.

**Science périphérique et géopolitique des savoirs.** Comment la position d'un
système scientifique dans la division internationale du travail scientifique
détermine ce que ses chercheurs jugent digne d'être communiqué — et dans quelle
langue.

**L'espace lusophone comme terrain.** Le Brésil, le Portugal et les pays
africains de langue officielle portugaise partagent une langue et un héritage
colonial, mais presque aucune de leurs conditions matérielles de recherche.
C'est le cadrage de la thèse en cours.

**Méthodes.** Sociologie computationnelle et analyse quantitative appliquée aux
sciences sociales&nbsp;: enquêtes comparatives, modèles de classes latentes,
R et Python.

## À la une

{% assign destaque = site.portfolio | sort: 'date' | reverse | first %}
{% if destaque %}
[**{{ destaque.title }}**]({{ destaque.url | relative_url }}) — {{ destaque.excerpt | strip_html | strip_newlines | truncate: 200 }}
{% endif %}

---

J'écris, je présente et je collabore en portugais, espagnol, anglais et français.
Contact&nbsp;: [mapereira@ufmg.br](mailto:mapereira@ufmg.br) ·
[CV](/cv/) ·
[ateliers et cours courts](/oficinas/)
