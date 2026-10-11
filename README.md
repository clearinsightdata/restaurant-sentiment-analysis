# Analyse de sentiment — Avis restaurants Tripadvisor

## Le problème
Un restaurateur reçoit des centaines d'avis clients par an.
Les lire manuellement un par un est impossible — il faut
un outil qui identifie automatiquement les points forts
et les axes d'amélioration.

## La solution
Modèle NLP d'analyse de sentiment appliqué à 1 502 vrais
avis Tripadvisor — classification automatique positive,
négative ou neutre avec extraction des thèmes clés.

## Résultats clés
- 📊 **1 502 avis réels** Tripadvisor analysés
- 🤖 **82.3% de précision** du modèle NLP
- 🔑 **Le service** est le facteur #1 cité positivement ET négativement
- 🌍 **7 restaurants** dans 7 pays comparés

## Classement par satisfaction

| Restaurant | Pays | Score polarité |
|-----------|------|---------------|
| Mosaic | Inde | 0.534 |
| Stara Kamienica | Pologne | 0.451 |
| The LOFT | Maroc | 0.425 |
| Ad Hoc Ristorante | Italie | 0.366 |
| Pelmenya | Russie | 0.322 |
| The Frog at Bercy Village | France | 0.322 |
| Old Square | Cuba | 0.286 |

## Mots clés identifiés

**Avis positifs** — great, food, service, excellent, delicious, staff, wonderful

**Avis négatifs** — service, terrible, disappointed, rude, expensive, bad, horrible

## Application 
Cette méthodologie s'applique directement aux avis Google
de n'importe quel restaurant  — identifier automatiquement
les points forts et faibles à partir de centaines d'avis clients.

## Stack technique
- **Python** — Pandas, TextBlob, WordCloud, Plotly
- **NLP** — Analyse de sentiment, extraction de mots clés
- **Données** — Tripadvisor via Kaggle (1 502 avis réels)

## Structure du projet
- data/reviews_clean.csv — Dataset 1 502 avis nettoyés
- notebooks/01_collecte_avis.ipynb — Chargement et exploration
- notebooks/02_analyse_sentiment.ipynb — Analyse NLP et visualisations
- images/wordcloud_sentiment.png — Nuage de mots

---
*Projet réalisé par [ClearInsightdata](https://github.com/clearinsightdata)*