# Stepwell House Website

Static homepage and contact page for Stepwell House — corporate luxury/heritage modern property management site.

## Structure

- `home.html` — Homepage: header, navigation, rotating hero carousel, and "Our Services" cards.
- `contact.html` — Contact page: contact details, live Google Maps embed, and inquiry form.
- `stepwell-*.png` — Image assets referenced by relative path from the HTML files (hero slides and service card icons).

## Usage

Open `home.html` in a browser. No build step or dependencies required — plain HTML/CSS/JS.

## Notes

- Fonts (Playfair Display, Inter) are loaded via Google Fonts CDN.
- The hero carousel auto-rotates every 10 seconds with a crossfade; carousel dots are clickable.
- The contact page embeds a live Google Maps iframe for the Croydon address.
