# 💻 Technical Test – Techno - Club

Ce projet est basé sur un design Figma fourni par Activis, que je réalise en HTML & Sass.

---

## 📄 Description

L'objectif est de reproduire le plus fidèlement possible le design fourni, en mettant l'accent sur :
- Une structure de code claire et maintenable
- Un CSS modulable et évolutif
- L'accessibilité et la responsivité

---

## ⚙️ Stack & Choix techniques

- **HTML5** : structure sémantique, balisage propre
- **Sass (SCSS)** : pour une meilleure organisation
    - Sass me permet de gagner en lisibilité et en réutilisabilité. Avec des fichiers découpés par fonctionnalités, il est plus simple de maintenir le code sur le long terme.
- **Pas de framework CSS** :
    - J'ai choisi de ne pas utiliser Bootstrap/Tailwind pour faire du design sur mesure, et garder un bundle léger.

---


Chaque section a son propre fichier SCSS pour favoriser l'isolation et la maintenance. Toutes les variables globales (couleurs, espacements, fonts) sont créées au fur et à mesure dans `_variables.scss`.

---

## 🚀 Workflow

- **Branches Git** :
    - `master` : branche stable
    - `feature/*` : développement de chaque section/page
- **Approche Desktop First** :
    - J'intègre d'abord le design desktop pour avoir une base solide, puis j'adapte la responsivité.
- **Design System** :
    - Je me réfère en permanence au Figma et au design system pour respecter la cohérence visuelle (espacements, typographies, couleurs).
    -
---


## Architecture

  techno-club
  ├─ README.md
  ├─ assets
  │  ├─ icons
  │  │  ├─ Arrow.svg
  │  │  ├─ Arrow_Down.svg
  │  │  ├─ Icon.svg
  │  │  ├─ Logo.svg
  │  │  ├─ Star.svg
  │  │  ├─ Stars Container.svg
  │  │  ├─ arrow-up.svg
  │  │  ├─ check.svg
  │  │  ├─ git-contour.svg
  │  │  ├─ git-interieur.svg
  │  │  ├─ github.svg
  │  │  ├─ linkedin.svg
  │  │  ├─ papillon.svg
  │  │  ├─ react.svg
  │  │  └─ typescript.svg
  │  ├─ illustrations
  │  │  ├─ Glow.svg
  │  │  ├─ Vector.svg
  │  │  ├─ glow-bg.svg
  │  │  └─ path158.svg
  │  └─ images
  │     ├─ Testimonials images.png
  │     ├─ features_image.jpg
  │     ├─ medium-shot-people-book-club 1.png
  │     ├─ people-library-reading-club-learning-from-books.png
  │     ├─ profile_01.jpg
  │     ├─ profile_02.jpg
  │     └─ profile_03.jpg
  ├─ css
  │  ├─ main.css
  │  └─ main.css.map
  ├─ index.html
  └─ scss
     ├─ abstracts
     │  └─ _variables.scss
     ├─ base
     │  ├─ _reset.scss
     │  └─ _typography.scss
     ├─ components
     │  ├─ _background.scss
     │  └─ _buttons.scss
     ├─ layout
     │  ├─ _footer.scss
     │  ├─ _grid.scss
     │  └─ _header.scss
     ├─ main.scss
     └─ pages
        ├─ _features.scss
        ├─ _footer.scss
        ├─ _home.scss
        ├─ _lecture.scss
        ├─ _payment.scss
        ├─ _reading_journey.scss
        ├─ _testimonial.scss
        └─ _top.scss
