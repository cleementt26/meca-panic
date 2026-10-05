# MÉCA PANIC — Le semestre impossible

**[Jouer dans le navigateur](https://cleementt26.github.io/meca-panic/)**

Un jeu de plateformes original dans une école d’ingénieurs : quatre univers distincts, huit guests sarcastiques, un mini-jeu de tir et beaucoup d’autodérision sur la formation. Décors dessinés dans le navigateur, double saut, checkpoints, dialogues et sons synthétisés.

## Le parcours

1. **L’atelier du chaos** — fonderie au coucher du soleil, convoyeurs, presses et engrenages. Prof. Couple et Le stagiaire accompagnent l’assemblage du prototype.
2. **La tour d’asservissement** — circuits lumineux, ascenseurs et drones électriques. Dr. PID et Maître Arduino commentent la fermeture de la boucle de contrôle.
3. **Pivotland** — campus du management, réunions en zigzag et plateformes de pitch. Kevin Synergie et Coach Pivot célèbrent les leviers, la synergie et l’intrapreneuriat exigeant. Retrouve trois preuves de travail réel pour sortir du bullshit.
4. **La soutenance finale** — bibliothèque suspendue, terrasses de dossiers et tampons hostiles. Madame ISO et Le jury attendent la livraison du prototype.

**Entre la tour PID et Pivotland : le banc d’essai.** Pilote un drone de maintenance à l’intérieur du prototype d’avion et neutralise trois noyaux défectueux avec ton pistolet à impulsions. La réparation te permet de reprendre le parcours à Pivotland.

Récupère les trois modules de chaque niveau pour ouvrir sa sortie. Saute sur les robots pour les désactiver. Après le quatrième univers, l’écran de fin affiche le diplôme et les statistiques ; tu peux recommencer une partie ou revenir à l’accueil.

## Commandes

| Action | Clavier |
| --- | --- |
| Se déplacer dans les plateformes | ← → ou Q D |
| Sauter / double saut | Espace ou ↑ |
| Parler aux guests | E ou ↓ |
| Carte du semestre | M |
| Pause | P ou Échap |
| Piloter le drone du mini-jeu | ← ↑ ↓ → |
| Tirer dans le mini-jeu | Espace ou X, maintenir |

Les boutons tactiles apparaissent sur les appareils compatibles. Le son s’active avec le bouton ♪. Le menu de pause permet aussi de revenir à l’accueil ou de recommencer.

## Jouer localement

Ouvre `index.html` dans un navigateur récent : cette version contient tout le jeu et ses polices, sans connexion requise. `meca-panic.html` est la même version autonome, utilisée par le lien de téléchargement dans le menu.

Pour travailler sur les sources séparées, télécharge et décompresse [l’archive des sources](meca-panic-github.zip). Depuis le dossier extrait :

```sh
python3 -m http.server 8000
```

Puis ouvre `http://localhost:8000/src/`.

## GitHub Pages

Le site statique est publié depuis la racine du dépôt, avec la branche `main` et le dossier `/ (root)`.

## Fichiers

- `index.html` : version autonome servie par GitHub Pages.
- `meca-panic.html` : version autonome téléchargeable.
- `.nojekyll` : publication des fichiers statiques sans transformation.
- `meca-panic-github.zip` : archive complète avec les sources modifiables dans `src/`, notamment les parcours dans `levels.js`, le mini-jeu dans `shooter.js` et les polices locales.

Les personnages, dialogues et visuels du jeu sont originaux et satiriques. Aucune affiliation avec une école ou une marque citée n’est revendiquée. Les polices **Barlow Condensed** et **DM Sans** sont accompagnées de leurs notices dans `src/fonts/` à l’intérieur de l’archive.
