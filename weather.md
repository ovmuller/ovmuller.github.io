---
layout: default
title: 7-day weather forecast
permalink: /weather/
---

{% include navigation.html %}

## 7-day weather forecast

Use your current location to retrieve a seven-day forecast. Your coordinates are sent only to the weather service and are not stored by this website.

<button id="load-forecast" class="forecast-button" type="button">Use my location</button>

<p id="forecast-status" class="forecast-status" role="status" aria-live="polite"></p>

<div id="forecast" class="forecast-grid" aria-label="Seven-day forecast"></div>

<p class="forecast-credit">Forecast data: <a href="https://open-meteo.com/" rel="noopener">Open-Meteo</a>.</p>

<script src="{{ '/assets/js/weather.js' | relative_url }}" defer></script>

