# Website update

Copy these files and folders into the root of your GitHub Pages repository.

Before publishing, add your portrait as:

`assets/images/profile.jpg`

A square image of at least 520 × 520 pixels works best. The CSS crops it into a circle without changing the source file.

Important: GitHub Pages expects the configuration filename to be `_config.yml` (with the leading underscore), not `config.yml`.

The weather page uses the visitor's browser location and the Open-Meteo API. It requires no API key. GitHub Pages serves over HTTPS, which is required for browser geolocation.
