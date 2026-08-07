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

.site-menu {
  display: flex;
  margin-bottom: 2rem;
  overflow: hidden;
  background: #155799;
  border-radius: 4px;
}

.site-menu a {
  flex: 1;
  padding: 0.8rem 1rem;
  color: white;
  font-weight: 600;
  text-align: center;
  text-decoration: none;
}

.site-menu a + a {
  border-left: 1px solid rgba(255, 255, 255, 0.45);
}

.site-menu a:hover,
.site-menu a.active {
  color: white;
  background: #0f3f70;
}
</style>

<nav class="site-menu" aria-label="Main navigation">
  <a href="{{ '/' | relative_url }}">Home</a>
  <a class="active" href="{{ '/weather/' | relative_url }}">7-day weather forecast</a>
</nav>
