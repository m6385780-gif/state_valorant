# Roster Tracker — Valorant

Suivi interactif des agents Valorant débloqués et de l'historique de parties (K/D/A, carte, mode, score), avec statistiques de performance et graphique d'évolution.

## Fonctionnalités

- Cocher les agents possédés, classés par rôle (Duelliste, Initiateur, Contrôleur, Sentinelle)
- Journaliser une partie : agent joué, carte, mode, score, éliminations/morts/assistances
- Historique des 30 dernières parties (sauvegarde locale complète)
- Graphique d'évolution du ratio K/D (fenêtre glissante des 30 dernières parties)
- Filtre par agent : top 3 / flop 3 des meilleures et pires parties
- Statistiques par carte : winrate, K/D moyen, éliminations moyennes
- % d'amélioration calculé sur l'ensemble de l'historique
- 100% responsive (mobile, tablette, desktop)

## Aperçu

Ouvre directement `index.html` dans un navigateur, ou visite la version publiée via GitHub Pages :
`https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`

## Structure du projet

Deux façons d'utiliser ce projet :

- **`index.html`** — version autonome (HTML + CSS + JS fusionnés en un seul fichier), la plus simple à héberger.
- **`page.html` + `couleur.css` + `le-reste.js`** — version avec fichiers séparés, plus facile à modifier/maintenir.

## Stockage des données

Les données (agents cochés, historique des parties) sont sauvegardées dans le `localStorage` du navigateur de chaque visiteur. Aucune donnée n'est envoyée à un serveur : chaque utilisateur a ses propres statistiques, privées et locales à son appareil.

## Technologies

HTML / CSS / JavaScript vanilla — aucune dépendance, aucun build nécessaire.

## Licence

Projet personnel, libre d'utilisation.
