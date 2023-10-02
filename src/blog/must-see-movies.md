---
title: Must-See Movies
author: Andrew Novosel
date: 2023-10-02
---

<body class="bg-gray-300">
  <h1 class="text-4xl font-mono text-center m-2">Must-See Movies</h1>
  <img class="mx-auto m-5" src="/images/must-see-movies.png" width="650px" />
  <p class="text-2xl m-5">In the sections that follow, you'll discover a curated collection of movie
    reviews, carefully selected to encompass cinematic experiences that I
    consider essential for every individual's journey through the world of film.
    These are not merely movies; they are profound and transformative narratives
    that I firmly believe should grace the screens of everyone at least once in
    their lifetime.</p>

  <section id="featured-articles" class="featured-articles">
    <div class="container flow">
      <h2 class="section-title text-2xl text-center">Recent articles</h2> 
      <ul role="list" class="articles__list flow text-xl m-5 leading-8">
        {%- for post in collections.movies | reverse -%} {% include
        'article-snippet.njk' %} {%- endfor %}
      </ul>
    </div>
  </section>
</body>