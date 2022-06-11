---
title: "{{ replace .Name "-" " " | title }}"
slug: "{{ .Name }}"
date: {{ .Date }}
summary: "Sommario per {{ .Name }}"
tags:
- Categorie
draft: false
# la parte tra ricetta/ e /images deve corrispondere allo slug
featured_image: "ricette/{{ .Name }}/images/copertina.jpg"
---
## Ingredienti
* Tanta
* Roba

## Preparazione
* Tanti
* Passi