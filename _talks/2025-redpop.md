---
title: "Dashboard interativo para análise de práticas e percepções de divulgação científica entre cientistas brasileiros"
collection: talks
type: "Talk"
permalink: /talks/2025-redpop
venue: "XIX Congresso RedPOP — Ciencia Viva: conectar mentes y comunidades"
date: 2025-09-11
location: "Puebla, México"
---

Apresentação em espanhol no XIX Congresso da RedPOP, realizado na Universidad
Popular Autónoma del Estado de Puebla, edição que marcou os 35 anos da rede.

## Resumo

A divulgação científica é peça central na relação entre ciência e sociedade,
mas a maior parte dos estudos analisa a percepção **do público** — não a dos
próprios cientistas. Esta apresentação parte dessa lacuna para mostrar como um
dashboard interativo pode servir simultaneamente à análise e à comunicação de
resultados de um survey sobre práticas e percepções de divulgação científica.

O argumento central é que **o dashboard pode ser um subproduto valioso da
própria pesquisa**: os mesmos dados que sustentam um artigo acadêmico podem
circular, sem custo adicional relevante, num formato explorável por gestores,
divulgadores e pelos próprios pesquisadores.

## Dados e ferramenta

- **Coleta:** questionário on-line autoaplicado, entre janeiro e março de 2023
- **População:** 15.800 bolsistas de produtividade em pesquisa (PQ) do CNPq,
  com 1.934 respondentes (12%)
- **Instrumento:** 51 perguntas distribuídas em 7 seções
- **Dashboard:** desenvolvido em Python com Streamlit, com filtros por variáveis
  sociodemográficas, comparação entre grupos, tabelas dinâmicas, gráficos de
  barras e de mosaico, e resíduos de Pearson para leitura das associações

**Acesse:** [cientistas-divulgacao.streamlit.app](https://cientistas-divulgacao.streamlit.app/)

## Limitações discutidas

Três, apresentadas explicitamente na sessão:

1. A população pesquisada é a **elite** da ciência brasileira — bolsistas PQ —,
   o que exige cautela com generalizações.
2. Os dados são **transversais**: não permitem inferência causal.
3. Alguns recursos do próprio dashboard, como o gráfico de mosaico, podem ser
   **difíceis de interpretar** para parte do público-alvo, o que reduz a
   acessibilidade dos resultados — uma limitação incômoda para uma ferramenta
   cujo propósito declarado é justamente ampliar o acesso.

## Materiais

- [Dashboard interativo](https://cientistas-divulgacao.streamlit.app/)
- [Slides](#) <!-- suba o PDF em /files/ e aponte aqui -->
