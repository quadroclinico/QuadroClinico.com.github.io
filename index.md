---
layout: index
title: "QuadroClinico.com"
---

## Páginas

- Buscador de [revisões no PubMed](busca-pubmed) (eu que fiz!)
- [Por onde estudar?](fontes-estudo)

## Últimas postagens

<ul>
  {% for post in site.posts %}
      <li>
        <span>{{ post.date | date: "%d/%m/%Y" }}</span>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
  {% endfor %}
</ul>


## Links úteis

- [Curso de digitação](https://www.edclub.com/pt-BR/library/bosque-da-digitacao) -- acredite, ajuda muito a agilizar sua vida nas admissões e altas (e é gratuito).
- [Criador de acrônimos](https://remember.shinyapps.io/remember_shiny_tool/) -- uso pra criar flashcards.
- [Zbib](https://zbib.org/) -- site que uso pra formatar referências.