---
layout: home
title: Accueil
nav_order: 0
comments: true
---

# L'antre du MD
## *L'aventure d'un jeune Maître du Donjon*

Ce site a pour objectif de fournir des ressources et des astuces précieuses à tous les passionnés de Donjons & Dragons, avec une attention particulière aux besoins des Maîtres du Donjon (ou Maîtres du Jeu). Bien que le contenu soit principalement axé sur la 5e édition, il est facilement adaptable à d'autres éditions de D&D ainsi qu'à d'autres jeux de rôle.

---

# Organisation du site


**[Articles](/articles.html)** : liste des différents articles de blog du site.

**[Aventures](/aventures/)** : contient les aventures One-Shot que j'ai pu créer, adapter ou mener.

**[Campagnes](/campagnes/)** : contient les campagnes que j'ai pu créer, adapter ou mener. Vous y retrouverez les éléments nécessaires au Maître du Donjon pour maîtriser les campagnes.

**[Outils & Ressources](/outils-ressources/)** : contient toutes les astuces, outils, ressources et sites en lien avec le jeu D&D pour les joueurs et les MD.

**[Bases de données](/donnees)** : quelques bases simples mais complètes comme les créatures, les objets magiques, les sorts,... avec leur source, le nom anglais pour faire un rapprochement plus rapide, et les descriptifs.

---


# Derniers articles

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      {{ post.date | date: "%Y-%m-%d" }} : <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[Voir tous les articles](/articles.html)

---


# Qui suis-je ?

Le jour je suis architecte de solutions chez Capgemini, travail dans lequel j'aime confronter la technique et les besoins pour concevoir des solutions adaptées, évolutives et scalables. La nuit je suis Maître du Donjon où je masterise des aventures et campagnes pour mes amis.

<p align="center"><img src="assets/profil.jpg" alt="Photo de Yann Jajkiewicz en noir et blanc." width="200" style="border-radius: 50%;" /></p>

<br/>
<hr>

# Support / Contact

Site web : [https://yann.me](https://yann.me)

Contact : contact@yann.me

