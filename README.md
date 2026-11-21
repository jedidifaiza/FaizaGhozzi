# Site personnel — Faiza Ghozzi

Site d'une page présentant mes activités d'enseignement, de recherche et de vie universitaire
(ISIMS, Université de Sfax · laboratoire MIRACL).

En ligne : https://jedidifaiza.github.io/FaizaGhozzi/

## Contenu du dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | Le site complet : contenu, mise en page (CSS) et interactions (JavaScript) |
| `photo.jpg` | Photo de profil, affichée en cercle (à ajouter, carrée de préférence) |
| `.nojekyll` | Indique à GitHub Pages de publier les fichiers tels quels |

## Mettre à jour le site

- **Ajouter une publication** : dans `index.html`, copier un bloc `<li class="pub" ...> ... </li>` dans l'année voulue.
  L'attribut `data-type` vaut `journal`, `intl`, `natl` ou `thesis`.
- **Changer les couleurs** : modifier les variables en haut du bloc `<style>` (section « Couleurs »).
- **Ajouter Google Scholar** : décommenter le lien prévu dans la section Profil.

Chaque modification envoyée sur la branche principale est publiée automatiquement par GitHub Pages en une minute environ.
