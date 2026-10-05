# MÉCA PANIC — Le semestre impossible

Un jeu de plateformes original dans une école d’ingénieurs : mécanique, mécatronique, robots mal réglés et autodérision sur la formation. Décors dessinés dans le navigateur, double saut, checkpoints, dialogues sarcastiques et sons synthétisés.

## Les quatre épreuves

1. **L’atelier du chaos** — mécanique appliquée et prototypes presque conformes.
2. **Le labo d’asservissement** — plateformes, robots et dépassements de consigne.
3. **Pivotland** — leviers, synergies, intrapreneuriat exigeant et posts LinkedIn : retrouver trois preuves de travail réel.
4. **La soutenance finale** — livrer le prototype au jury et survivre à « une petite question ».

Récupère les trois modules de chaque niveau pour ouvrir sa sortie. Saute sur les robots pour les désactiver.

## Commandes

| Action | Clavier |
| --- | --- |
| Se déplacer | ← → ou Q D |
| Sauter / double saut | Espace ou ↑ |
| Parler aux guests | E ou ↓ |
| Pause | P ou Échap |

Les boutons tactiles apparaissent sur les appareils compatibles. Le son s’active avec le bouton ♪.

## Jouer localement

Ouvre `index.html` dans un navigateur récent : cette version contient tout le jeu et ses polices, sans connexion requise. `meca-panic.html` est la même version autonome, utilisée par le lien de téléchargement dans le menu.

Pour travailler sur les sources séparées, télécharge et décompresse [l’archive des sources](meca-panic-github.zip). Depuis le dossier extrait :

```sh
python3 -m http.server 8000
```

Puis ouvre `http://localhost:8000/src/`.

## GitHub Pages

Le site statique est prêt à être publié depuis la racine du dépôt. Dans **Settings → Pages**, choisis **Deploy from a branch**, puis la branche `main` et le dossier `/ (root)`.

## Fichiers

- `index.html` : version autonome servie par GitHub Pages.
- `meca-panic.html` : version autonome téléchargeable.
- `.nojekyll` : publication des fichiers statiques sans transformation.
- `meca-panic-github.zip` : archive complète avec les sources modifiables dans `src/` et les polices locales.

Les personnages, dialogues et visuels du jeu sont originaux et satiriques. Aucune affiliation avec une école ou une marque citée n’est revendiquée. Les polices **Barlow Condensed** et **DM Sans** sont accompagnées de leurs notices dans `src/fonts/` à l’intérieur de l’archive.
