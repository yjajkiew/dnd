---
layout: home
title: Accueil
nav_order: 0
comments: true
---

# L'antre du MD
### *ou l'aventure d'un jeune Maître du Donjon*

Ce site vise à fournir des ressources et astuces utiles à tous ceux impliqués dans le monde de D&D avec un orientation plus forte sur les éléments qui concernent le Maître du Donjon ou Maître du Jeu. Le contenu se concentre spécifiquement sur la 5e édition mais il peut facilement être appliqué à toutes les autres éditions de D&D ou à d'autres jeux de rôle.

---

# Organisation du site


**[Articles](/articles.html)** : liste des différents articles de blog du site.

**[Aventures](/aventures/)** : contient les aventures One-Shot que j'ai pu créer, adapter ou mener.

**[Campagnes](/campagnes/)** : contient les campagnes que j'ai pu créer, adapter ou mener. Vous y retrouverez les éléments nécessaires au Maître du Donjon pour maîtriser les campagnes.

**[Outils & Ressources](/outils-ressources/)** : contient toutes les astuces, ressources et sites en lien avec le jeu D&D qui conviennent aux joueurs et aux MD.

**[Maître du Donjon (MD)](/maitre-du-donjon/)** : toute la panoplie des ressources indispensables du Maître du Donjon avec des tables aléatoires, des outils pour la musique, les outils pour créer un monde et des cartes, etc.

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


---


# Qui suis-je ?

Le jour je suis architecte de solutions chez Capgemini, travail dans lequel j'aime confronter la technique et les besoins pour concevoir des solutions adaptées, évolutives et scalables.

<p align="center"><img src="assets/profil.jpg" width="200" style="border-radius: 50%;" /></p>

<br/>
<hr>

# Support / Contact

Site web : [https://yann.me](https://yann.me)

Contact : contact@yann.me

