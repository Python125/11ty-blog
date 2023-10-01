---
title: Must-See Movies
author: Andrew Novosel
date: 2023-10-02
tags: ["post", "featured"]
image: /images/must-see-movies.png
---

<h1 class="text-4xl font-mono text-center">Must-See Movies</h1>
<p class="text-2xl m-4">Below, you will find reviews of movies that I believe everyone should see at least once in their lifetime.</p>

<section id="featured-articles" class="featured-articles">
  <div class="container flow">
    <h2 class="section-title">Recent articles</h2>
    <ul role="list" class="articles__list flow text-lg m-2 leading-8">
      {%- for post in collections.featured | reverse -%}
        {% include 'article-snippet.njk' %}
      {%- endfor %}
    </ul>
  </div>
</section>