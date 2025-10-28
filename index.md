---
layout: index
title: "QuadroClinico.com"
---

## Páginas

- Buscador de [revisões no PubMed](busca-pubmed) (eu que fiz!)
- [Por onde estudar?](fontes-estudo)

## Últimas postagens

<ul class="posts">
  {% for post in site.posts %}
      {% assign post_time = post.date | date: '%s' %}
      {% assign now = 'now' | date: '%s' %}
      {% assign diff = now | minus: post_time %}
      <li>
        <span class="posts-dates">{{ post.date | date: "%d/%m/%Y" }}</span> <span class="break"></span>
        <a href="{{ post.url }}" class="post-title">{{ post.title }}</a>
          {% if diff < 2592000 %}
          <span class="novo-badge"><i>Novo!</i></span>
          {% endif %}
      </li>
  {% endfor %}
</ul>


## Links úteis

- [Curso de digitação](https://www.edclub.com/pt-BR/library/bosque-da-digitacao) -- acredite, ajuda muito a agilizar sua vida nas admissões e altas (e é gratuito).
- [Criador de acrônimos](https://remember.shinyapps.io/remember_shiny_tool/) -- uso pra criar flashcards.
- [Zbib](https://zbib.org/) -- site que uso pra formatar referências.