Vincent Bastille — Soundtracks mini-site
========================================

Ce dossier contient un mini-site statique ultra simple, pensé pour être déployé
sur Vercel / Render / GitHub Pages et optimisé SEO pour Google :

- `index.html` : page d'accueil avec présentation, cartes des soundtracks.
- `mystic.html` : page SEO dédiée à "Mystic — Original Soundtrack".
- `le-lac-ost.html` : page SEO dédiée à "Le Lac — Original Motion Picture Soundtrack".
- `assets/styles.css` : styles globaux.
- `robots.txt` + `sitemap.xml` : indispensables pour Google Search Console.

A faire avant déploiement :
- si besoin, remplacer le domaine `https://soundtracks.vincentbastille.online`
  dans `index.html`, `mystic.html`, `le-lac-ost.html`, `robots.txt`, `sitemap.xml`
  par le domaine réel où tu déploies le site.
- (optionnel) remplacer les liens Spotify génériques par les URLs d'albums.

Ensuite : push sur un repo Git + déploiement sur Vercel / Render, puis
déclaration du domaine dans Google Search Console et envoi du sitemap.