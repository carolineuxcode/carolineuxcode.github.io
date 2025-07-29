---
layout: default
title: Meus Projetos
---

## Projetos

<ul>
  {% for projeto in site.data.projetos %}
    <li>
      <strong>{{ projeto.nome }}</strong><br>
      {{ projeto.descricao }}<br>
      <a href="{{ projeto.link }}" target="_blank">Ver projeto</a>
    </li>
  {% endfor %}
</ul>
