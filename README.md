# Impressum – Agentur-Credit (5 Entwürfe)

Five animated design options for the "Konzept, Design und Umsetzung" credit section on the Impressum page.

- `index.html` – shows all five designs together
- `designs/01-aura.html` – dark card with a rotating light border
- `designs/02-welle.html` – light card with a flowing wave panel
- `designs/03-laufband.html` – full-width black band with scrolling outline text
- `designs/04-spotlight.html` – cursor glow, the three steps light up on scroll
- `designs/05-signatur.html` – minimal, the logo writes itself like a signature
- `assets/lm-logo.png` – logo (cropped from a screenshot; swap in the original file for best sharpness)

## Using a design in WordPress / Elementor

Each design file is self-contained. Copy the `<style>` block, the `<section>` and (for 04 and 05) the `<script>` into an HTML widget. Then:

1. Replace `../assets/lm-logo.png` with the logo URL from the media library.
2. Check the agency link (`https://www.landsberger-medienagentur.de`) and change it if needed.

All animations switch off automatically for visitors who have reduced motion turned on.
