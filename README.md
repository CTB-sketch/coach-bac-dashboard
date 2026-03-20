# Coach Bac — Centre de Pilotage

Dashboard de pilotage stratégique pour coach scolaire spécialisé Bac de Français & Grand Oral.

## Fonctionnalités

- **Page d'accueil** — synthèse KPIs + frise chronologique interactive
- **Frise chronologique** — visualisation du temps jusqu'au Bac avec jalons et niveaux de priorité
- **Tracker 90 jours** — objectifs business + revenus mensuels saisissables
- **Stratégie LinkedIn** — plan d'actions classé + calendrier 4 semaines + projections
- **Connexions LI/90j** — lien entre actions LinkedIn et objectifs business
- **To-do list** — tâches cochables avec progression
- **Prompts Gemini** — 4 prompts prêts à l'emploi copiables en un clic
- **Journal quotidien** — notes avec historique

## Données

Toutes les données sont sauvegardées localement dans le navigateur (localStorage). Aucun serveur, aucune base de données.

## Déploiement

Ce projet est déployé automatiquement sur Vercel à chaque push sur la branche `main`.

## Mise à jour

Pour mettre à jour le dashboard :
1. Remplacer `index.html` sur GitHub
2. Vercel redéploie automatiquement en ~30 secondes

## Stack technique

- React 18 (UMD, sans bundler)
- SVG pur pour les graphiques (aucune dépendance externe)
- localStorage pour la persistance des données
- Google Fonts : Playfair Display + Lato
