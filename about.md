---
layout: page
title: About Us
permalink: /about/
---

<h1>Meet the Team</h1>

<style>
  .team-container {
    display: flex;
    flex-wrap: wrap;              /* ✅ wrap nicely on smaller screens */
    justify-content: center;
    gap: 2rem;                    /* space between members */
    margin-top: 2rem;
  }
  .team-member {
    text-align: center;
    flex: 1 1 200px;              /* grow/shrink, min width ~200px */
    max-width: 250px;
  }
  .team-member img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
    object-fit: cover;            /* ✅ ensures circle crop without stretching */
    aspect-ratio: 1 / 1;          /* ✅ keeps it square always */
  }
</style>

<div class="team-container">
  <div class="team-member">
    <a href="{{ '/about/atharv' | relative_url }}">
      <img src="{{ site.baseurl }}/assets/images/Atharv.jpg" alt="Atharv Tambade">
      <h3>Atharv</h3>
    </a>
  </div>

  <div class="team-member">
    <a href="{{ '/about/aadityan' | relative_url }}">
      <img src="{{ site.baseurl }}/assets/images/aadityan.jpg" alt="Aadityan Ganesh">
      <h3>Aadityan</h3>
    </a>
  </div>
</div>
