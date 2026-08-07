---
layout: default
permalink: /weather/
---

<style>
  .site-menu {
    display: flex;
    margin-bottom: 2rem;
    background: #155799;
  }

  .site-menu a {
    padding: 0.8rem 1rem;
    color: white;
    font-weight: 600;
    text-decoration: none;
  }

  .site-menu a:hover,
  .site-menu a.active {
    background: #0f3f70;
  }
</style>

<nav class="site-menu" aria-label="Main navigation">
  <a href="{{ '/' | relative_url }}">Home</a>
  <a class="active" href="{{ '/weather/' | relative_url }}">7-day weather forecast</a>
</nav>
