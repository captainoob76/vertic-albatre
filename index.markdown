---
layout: default
title: Accueil
permalink: /
hero_image: "/assets/images/escalade-hero.jpg" # À créer/remplacer
---

## ⛰️ Bienvenue au Club d'Escalade Vertic'Albâtre !

**Vertic'Albâtre** est votre club d'escalade sur la Côte d'Albâtre. Que vous soyez débutant curieux ou grimpeur confirmé, rejoignez notre communauté pour partager notre passion pour la verticalité, en salle et en extérieur.

### 🎯 Notre Mission

* **Former** les grimpeurs aux techniques de sécurité et de progression.
* **Organiser** des sorties sur les plus beaux sites de la région (et au-delà !).
* **Créer** un environnement convivial et stimulant pour tous les âges.

---

## 📅 Prochains Événements Clés

Ne manquez pas nos rendez-vous !

| Événement | Date | Lieu | Public |
| :--- | :--- | :--- | :--- |
| **Séance Découverte Gratuite** | Samedi 10 décembre | Salle locale | Débutants |
| **Sortie Falaise 'Les Dalles'** | Dimanche 18 décembre | Site extérieur | Confirmés |
| **Assemblée Générale Annuelle** | Vendredi 13 janvier | Maison du Quartier | Membres |

[**Voir le calendrier complet →**](/calendrier)

---

## 📰 Dernières Actualités et Dossiers

Découvrez les récits de nos dernières sorties, les conseils d'entraînement, et toutes les informations importantes du club directement dans notre section blog. C'est ici que nos membres partagent leurs expériences !

<div class="posts-list">
  {% for post in site.posts limit: 3 %}
  <article class="post-item">
    <div class="post-content">
      <h3 class="post-title"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <p class="post-meta">Publié le {{ post.date | date: "%-d %B %Y" }} par {{ post.author }}</p>
      <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
      <a href="{{ post.url | relative_url }}" class="read-more">Lire la suite →</a>
    </div>
  </article>
  {% endfor %}
</div>

<p class="view-all-link">
  <a href="/blog">**Consulter tous les Dossiers Verticaux →**</a>
</p>