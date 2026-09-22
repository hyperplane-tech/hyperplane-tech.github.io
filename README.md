# hyperplane-tech.github.io

Site vitrine d'Hyperplane, formation et conseil en intelligence artificielle.
Site statique généré avec Jekyll, publié par GitHub Pages sur
<https://www.hyperplane.fr>.

## Structure

```
_config.yml            configuration Jekyll du site
_layouts/
  default.html         gabarit principal (head, header, main, footer, scripts)
_includes/
  head.html            balises <head>, métadonnées SEO/Open Graph, polices, css
  header.html          en-tête de site, logo SVG et navigation
  footer.html          pied de page et liens
index.html             page principale (sections accueil, formations, conseil, approche, à propos, contact)
mentions-legales.html  mentions légales
404.html               page d'erreur servie par GitHub Pages
assets/style.css       feuille de style unique, thème clair et sombre
assets/site.js         menu mobile et année du pied de page
assets/favicon.svg     favicon
CNAME                  domaine personnalisé, géré par GitHub Pages
robots.txt sitemap.xml
```

## Développement local

Prérequis : Ruby, Bundler et Jekyll.

```
bundle install
bundle exec jekyll serve
```

Le site est ensuite accessible sur <http://localhost:4000>.

## Publication

Tout push sur `main` déclenche le déploiement GitHub Pages, en général en moins
d'une minute.

## À compléter

Les emplacements à renseigner sont signalés par un commentaire `TODO` dans le code.

- [ ] adresse de contact définitive (`contact@hyperplane-tech.com` est un espace réservé)
- [ ] intitulés, durées et publics réels du catalogue de formations
- [ ] paragraphe de présentation et biographie dans la section « À propos »
- [ ] mentions légales : forme juridique, siège, SIREN, TVA, déclaration d'activité
- [ ] image de partage `og:image` (1200 × 630) pour les aperçus sur les réseaux
