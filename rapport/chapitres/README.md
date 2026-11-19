# Sous-dossier des Chapitres (`rapport/chapitres/`)

Ce sous-dossier contient les chapitres unitaires qui composent le rapport du projet Blog des Lauréats.

## 1. Rôle du sous-dossier

- Découper la rédaction du rapport en modules indépendants et clairs.
- Permettre à l'apprenant de se concentrer sur un chapitre spécifique à la fois.
- Faciliter le travail collaboratif et les revues de documentation.

## 2. Chapitres inclus

- `3.md` : introduction (contexte, objectifs et démarche méthodologique).
- `25.md` : conclusion (synthèse des acquis, bilan technique et perspectives d'évolution).

Entre ces deux chapitres, le rapport couvre le cadrage du projet, la méthodologie (Scrum, 2TUP, Design Thinking), la planification, la branche fonctionnelle avec les cas d'utilisation, la branche technique et l'architecture (Laravel, MVC, architecture 3-tiers, MySQL), puis la conception et la réalisation.

## 3. Règle de nommage et compilation

- Chaque fichier est nommé par son numéro d'ordre (`1.md`, `2.md`, ..., `25.md`), ce qui fixe sa position sans aucune liste écrite dans le script.
- Chaque fichier commence par un titre Markdown de niveau 1 ; le script le reprend tel quel, sans ajouter de numéro. Avec un nom numérique, ce titre est indispensable.
- `2.md` contient le titre « Table des matières » et le marqueur `<!-- SOMMAIRE -->` : le script y insère la liste des titres des chapitres.
- Le script `../concat-chapitres.js` assemble automatiquement tous les fichiers `.md` du dossier et génère le rapport consolidé `rapport.md`.
