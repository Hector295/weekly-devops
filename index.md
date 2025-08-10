---
title: Blog DevOps Automático
layout: default
---

# 🚀 Blog DevOps Automático

Este blog se actualiza **cada semana** con un nuevo artículo técnico sobre Docker, Linux, DevOps y automatización.

Los artículos son generados por **IA (Gemini)**, revisados por [HectorVC](https://github.com/Hector295), y publicados automáticamente mediante GitHub Actions.

👉 Artículos recientes:

<ul>
{% for post in site.posts limit:10 %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> - <em>{{ post.date | date: "%d/%m/%Y" }}</em></li>
{% endfor %}
</ul>

➡️ [Ver todos los artículos](/_posts)
