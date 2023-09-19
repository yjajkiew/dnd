---
layout: home
title: Accueil
nav_order: 0
comments: true
---

# L'aventure d'un jeune Maître du Donjon

Ce site vise à fournir des ressources et astuces utiles à tous ceux impliqués dans le monde de D&D. Le contenu se concentre spécifiquement sur la 5e édition mais il peut facilement être appliqué à toutes les autres éditions de D&D ou à d'autres jeux de rôle.

---


# Derniers articles

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>


---


# Qui suis-je ?

Le jour je suis architecte de solutions chez Capgemini, travail dans lequel j'aime confronter la technique et les besoins pour concevoir des solutions adaptées, évolutives et scalables.

<p align="center"><img src="assets/profil.jpg" width="200" style="border-radius: 50%;" /></p>

<br/>
<hr>

# Support / Contact

Site web : [https://yann.me](https://yann.me)

Contact : contact@yann.me

