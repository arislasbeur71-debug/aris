# Portfolio Aris Lasbeur

Portfolio de **Aris Lasbeur**, développeur web freelance à Tizi Ouzou (Algérie) : sites vitrines pour entreprises, boutiques en ligne, systèmes de réservation et plateformes e-learning, avec SEO et suivi.

Site statique en **HTML, CSS et JavaScript** (sans framework, sans dépendance externe).

## Structure

```
portfolio/
├── index.html            Page unique (accueil, services, réalisations, à propos, méthode, contact)
├── css/
│   ├── style.css         Styles (variables, sections, responsive, mode sombre)
│   ├── fonts.css         Polices Outfit et Manrope hébergées localement
│   └── icons.css         Icônes Phosphor (sous-ensemble des icônes utilisées)
├── js/main.js            Menu mobile, filtres des réalisations, animations au défilement
├── assets/
│   ├── img/              Photo (aris-lasbeur.webp) et image de partage (og-image.jpg)
│   ├── fonts/            Fichiers de polices et d'icônes
│   └── projets/          Captures d'écran des réalisations (à ajouter)
├── favicon.svg
├── robots.txt
└── sitemap.xml
```

## Fonctionnalités

- Design responsive (mobile, tablette, ordinateur) et mode sombre automatique
- Bouton WhatsApp dans l'en-tête, dans l'accueil, dans le contact, et bouton flottant toujours visible
- Réalisations filtrables (boutiques en ligne, réservation, sites vitrines)
- SEO : balises meta, Open Graph, données structurées Schema.org, sitemap, robots.txt
- Accessibilité : lien d'évitement, focus visible, textes alternatifs, respect de « réduire les animations »
- Aucune requête externe : polices et icônes hébergées dans le projet (chargement rapide)

## Ajouter les captures d'écran des réalisations

Déposez une image par site dans `assets/projets/`, au format **WebP, 1200 x 750 px**, avec ces noms :

| Site | Fichier |
| --- | --- |
| boutique-lahna.com | `boutique-lahna.webp` |
| sourci-dz.com | `sourci-dz.webp` |
| el-ferdja-el-djamila.dz | `el-ferdja-el-djamila.webp` |
| fyneliatravel.dz | `fyneliatravel.webp` |
| drivevtcparis.fr | `drivevtcparis.webp` |
| hotel-alexandra.fr | `hotel-alexandra.webp` |
| aznay.fr | `aznay.webp` |
| taxi-sam35.fr | `taxi-sam35.webp` |
| adelconst.fr | `adelconst.webp` |
| logistor.fr | `logistor.webp` |

L'image s'affiche automatiquement. Tant qu'elle manque, une couverture avec le nom du site est affichée.

## Mettre en ligne avec GitHub Pages

1. Créez un dépôt sur GitHub (par exemple `portfolio`) et envoyez-y le contenu de ce dossier.
2. Dans le dépôt : **Settings > Pages > Source : Deploy from a branch**, branche `main`, dossier `/ (root)`.
3. Votre site sera en ligne à l'adresse `https://VOTRE-NOM.github.io/portfolio/`.
4. Remplacez `VOTRE-NOM.github.io/portfolio` par votre vraie adresse dans `index.html` (balise `canonical`), `robots.txt` et `sitemap.xml`.

## Tester en local

Ouvrez un terminal dans le dossier puis lancez :

```bash
python -m http.server 8000
```

et ouvrez `http://localhost:8000`.

## Contact

- WhatsApp / Téléphone : +213 6 75 97 80 96
- E-mail : arislasbeur71@gmail.com
