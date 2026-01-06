# Transport ST Sahel - Analyse descriptive de l'offre

Ce projet presente une analyse descriptive de l'offre de transport de la ST Sahel a partir
des donnees GTFS (routes, stops, trips, stop-times). L'objectif est de caracteriser
l'organisation des lignes, la frequence des trajets et les plages horaires de service.

## Contenu du depot

- Rapport Quarto: `qmd/sts-offre-transport.qmd`
- Donnees GTFS: `qmd/data/STS/`
- Configuration Quarto: `_quarto.yml`
- Sortie site: `docs/`

## Resultats principaux (resume)

- Statistiques globales: nombre de lignes, arrets, trajets, amplitude horaire.
- Repartition par ligne: top 10 lignes, part des trajets, frequence moyenne/heure.
- Heures de pointe: analyse matin/soir.
- Visualisations: histogrammes, boxplot, top lignes, repartition horaire.

## Comment executer

Prerequis: R + Quarto.

1) Rendu du rapport:
   - `quarto render`
2) Ouvrir le resultat:
   - `docs/index.html`

## Site web

https://oumarouahmed.github.io/Projet_R/

## Slides / Presentation

- Quarto: slides/presentation.qmd

## Structure des donnees

Les fichiers GTFS utilises:
- `routes.txt`
- `stops.txt`
- `trips.txt`
- `stop-times.txt`

## Auteur

Ahmed Oumarou



