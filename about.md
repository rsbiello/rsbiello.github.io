---
layout: page
title: About
permalink: /about/
---

<style>
.about-grid {
  grid-template-columns: minmax(0, 22rem) minmax(0, 1fr);
  gap: clamp(1.5rem, 4vw, 3.5rem);
}
.about-grid .portrait img { width: 100%; height: auto; }
.about-grid .profile-links { display: flex; flex-wrap: wrap; gap: .35rem 1rem; }
.about-grid h2 { margin-block: 1.75rem .75rem; font-size: clamp(1.9rem, 3vw, 2.5rem); }
.about-grid ul { margin: 0; padding-left: 1.2rem; }
.about-grid li + li { margin-top: .4rem; }
@media (max-width: 48rem) {
  .about-grid { grid-template-columns: minmax(0, 1fr); }
  .about-grid .portrait { max-width: 17rem; }
}
</style>

<div class="about-grid" markdown="1">
<figure class="portrait">
  <img src="{{ '/extras/467E625F-D0F8-4841-B600-98931CBEC874.mod.jpg' | relative_url }}" alt="Roberto Biello">
</figure>
<div markdown="1">

I’m an evolutionary biologist and conservation genomicist, currently a Marie Skłodowska-Curie Postdoctoral Fellow in the Morales Lab at the Globe Institute, University of Copenhagen.

I use genomic data to study how population decline, isolation, and demographic history shape genetic diversity in species of conservation concern. My fellowship project, [REVEAL]({{ '/research/#reveal' | relative_url }}), combines comparative genomics, simulations, and machine learning to test when genomic erosion can help predict extinction risk.

Before moving to Copenhagen, I held postdoctoral positions at the University of Ferrara and the John Innes Centre. I earned my PhD at the University of Ferrara with Giorgio Bertorelle and spent part of my doctoral training at the University of Edinburgh and Griffith University.

<p class="profile-links">
  <a href="mailto:r.s.biello@gmail.com">Email me</a>
  <a href="https://scholar.google.com/citations?user=yTnUnBEAAAAJ&amp;hl=en">Google Scholar</a>
  <a href="https://orcid.org/0000-0002-5916-884X">ORCID</a>
</p>

## Professional memberships

- **IUCN Species Survival Commission (IUCN SSC)** · Member
- **Società Italiana di Biologia Evoluzionistica (SIBE)** · Executive Committee member
- **Italian Group in Conservation Genetics and Genomics (GGC)** · Member since 2025
- **European Reference Genome Atlas (ERGA)** · Member since 2023
- **Amphibian Genomics Consortium (AGC)** · Member since 2023

</div>
</div>
