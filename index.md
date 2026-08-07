---
layout: default
permalink: /
---

<style>
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
  
  .profile-photo {
    float: right;
    width: 220px;
    height: 220px;
    margin: 0 0 1rem 2rem;
    border-radius: 50%;
    object-fit: cover;
  }

  @media (max-width: 600px) {
    .profile-photo {
      float: none;
      display: block;
      margin: 0 auto 1.5rem;
    }
  }
</style>

<nav class="site-menu" aria-label="Main navigation">
  <a class="active" href="{{ '/' | relative_url }}">Home</a>
  <a href="{{ '/weather/' | relative_url }}">7-day weather forecast</a>
</nav>

<img class="profile-photo" src="{{ '/profile.jpg' | relative_url }}" alt="Portrait of Omar V. Müller">

## About me

I am a climate scientist working on regional climate modelling, hydrology and climate variability over South America.

## Research

My research focuses on:

- Regional climate modelling
- Hydrological modelling
- River discharge
- Climate variability and prediction
- Scientific visualization

## Forecasts and visualizations

## Contact

[ovmuller@gmail.com](mailto:ovmuller@gmail.com)
