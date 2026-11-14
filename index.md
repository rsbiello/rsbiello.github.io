---
layout: default
title: Home
---

<section class="hero" aria-labelledby="home-title">
  <div class="hero-copy">
    <p class="eyebrow">Conservation and population genomics</p>
    <h1 id="home-title">What can genomes tell us about extinction risk?</h1>
    <p>I’m Roberto Biello, a Marie Skłodowska-Curie Postdoctoral Fellow at the Globe Institute, University of Copenhagen. I study how population decline and isolation shape genetic diversity in wild populations.</p>
    <div class="hero-links">
      <a class="button" href="{{ '/research/' | relative_url }}">Explore my research <span aria-hidden="true">↗</span></a>
      <a href="{{ '/publications/' | relative_url }}">Publications</a>
    </div>
  </div>
  <figure class="hero-image">
    <img src="{{ '/public/tortoise-close-up.webp' | relative_url }}" alt="Close-up of a young tortoise resting in a hand" fetchpriority="high" decoding="async">
    <figcaption>Photo by Roberto Biello · AI-assisted edit</figcaption>
  </figure>
</section>

<section class="featured" aria-labelledby="featured-title">
  <h2 id="featured-title">Featured research</h2>
  <div class="project-grid">
    <article class="project-card project-feature">
      <p class="eyebrow">Marie Skłodowska-Curie fellowship</p>
      <h3><a href="{{ '/research/' | relative_url }}#reveal">REVEAL</a></h3>
      <p>I combine bird genomes, simulations, and machine learning to test when genomic erosion can help predict extinction risk.</p>
    </article>
    <article class="project-card">
      <p class="eyebrow">Rough periwinkle</p>
      <h3><a href="{{ '/research/' | relative_url }}#fiasco">FIASCO</a></h3>
      <p>Why do some colonizations succeed while others fail?</p>
    </article>
    <article class="project-card">
      <p class="eyebrow">Marine conservation</p>
      <h3><a href="{{ '/research/' | relative_url }}#fin-whales">Fin whale genomics</a></h3>
      <p>What do genomes reveal about the history and connectivity of Mediterranean fin whales?</p>
    </article>
  </div>
</section>
