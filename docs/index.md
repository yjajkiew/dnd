---
layout: home
title: Accueil
nav_order: 0
comments: true
---

# L'antre du MD
## *L'odyssée d'un Maître du Donjon*

Bienvenue sur mon blog dédié à l'univers fascinant de Donjons & Dragons ! Ce site a pour mission de vous offrir une multitude de ressources et d'astuces essentielles pour tous les passionnés de D&D, en mettant un accent particulier sur les besoins des Maîtres du Donjon (ou Maîtres du Jeu). Bien que le contenu soit principalement orienté vers la 5e édition, il est conçu pour être facilement adaptable à d'autres éditions de D&D ainsi qu'à d'autres jeux de rôle.

---

# Organisation du site


**[Articles](/articles.html)** : découvrez une liste variée d'articles de blog, couvrant des thèmes passionnants et des conseils pratiques.

**[Aventures](/aventures/)** : explorez les aventures One-Shot que j'ai créées, adaptées ou menées, prêtes à être intégrées dans vos campagnes.

**[Campagnes](/campagnes/)** : retrouvez les campagnes que j'ai élaborées, avec tous les éléments nécessaires pour aider les Maîtres du Donjon à orchestrer des récits épiques.

**[Outils & Ressources](/outils-ressources/)** : accédez à une collection d'astuces, d'outils, de ressources et de sites web en lien avec l'univers de D&D, tant pour les joueurs que pour les MD.

**[Bases de données](/donnees)** : consultez des bases de données simples mais complètes, incluant des informations sur les créatures, les objets magiques, les sorts, etc. Chaque entrée est accompagnée de sa source, du nom en anglais pour un rapprochement rapide, et d'une description détaillée.

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

Le jour, je suis architecte de solutions chez Capgemini, où j'aime allier technique et besoins clients pour concevoir des solutions adaptées, évolutives et scalables. La nuit, je me transforme en Maître du Donjon, orchestrant des aventures et des campagnes épiques pour mes amis, plongeant avec eux dans des univers fantastiques où l'imagination n'a pas de limites.

<p align="center"><img src="assets/profil.jpg" alt="Photo de Yann Jajkiewicz en noir et blanc." width="200" style="border-radius: 50%;" /></p>

<br/>
<hr>

# Support / Contact

Site web : [https://yann.me](https://yann.me)

Contact : contact@yann.me

