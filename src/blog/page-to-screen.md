---
title: Page To Screen
author: Andrew Novosel
---

<body class="bg-orange-100">
  <h1 class="text-4xl font-bold text-center m-2">Page To Screen</h1>
  <img class="mx-auto m-5" src="/images/page-to-screen.png" width="650px" />
  <p class="m-5 text-2xl">
    Have you ever felt anticipation for a book-to-movie adaptation, only to find
    yourself disappointed by how the movie strays from the author's original
    intent? If so, you're not alone. This page is dedicated to examining the
    changes that movies often make when adapting from books. Join me as we
    explore these adaptations and the shifts that can occur between the written
    word and the silver screen.
  </p>

  <section id="featured-articles" class="featured-articles">
    <div class="container flow">
      <h2 class="section-title text-2xl text-center">Recent articles</h2>
      <ul role="list" class="articles__list flow text-lg m-5 leading-8">
        {%- for post in collections.book -%}
          {% include 'article-snippet.njk' %}
        {%- endfor %}
      </ul>
    </div>
  </section>
</body>