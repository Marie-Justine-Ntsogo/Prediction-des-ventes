### 📊 Analyse Prédictive des Ventes

Bienvenue dans mon premier projet GitHub 
Ce dépôt contient une analyse exploratoire et prédictive des ventes basée sur un jeu de données de type retail. Il combine Python (pandas, scikit-learn, plotly) pour l’analyse et Power BI pour la visualisation interactive.

## 🎯 Objectifs

Comprendre les tendances de vente passées

Créer des visualisations interactives (Python & Power BI)

Construire un modèle de prédiction de ventes (machine learning)

## 🗂️ Structure du projet

projet-vente/
├── data/                  # Données brutes CSV
│   └── superstore.csv
├── notebooks/             # Notebook principal
│   └── analyse_ventes.ipynb
├── README.md              # Ce fichier de présentation
├── requirements.txt       # Liste des packages Python 

##📁 Données utilisées

Source du jeu de données:https://www.kaggle.com/datasets/pratyushakar/rossmann-store-sales?select=store.csv

Le jeu de données  comprend :
# 📂 Détails des fichiers et des variables

Le dataset **Rossmann Store Sales** contient des données historiques pour 1 115 magasins. Le but est de prédire la variable `Sales` pour le jeu de test.

# 📁 Fichiers disponibles

| Nom du fichier        | Description |
|-----------------------|-------------|
| `train.csv`           | Données historiques des ventes incluant `Sales` |
| `test.csv`            | Données similaires sans la colonne `Sales`, utilisées pour les prédictions |
| `store.csv`           | Informations complémentaires sur les magasins |
| `sample_submission.csv` | Exemple de format de prédiction pour la soumission |

---

# 🧾 Description des variables

| Variable                         | Description |
|----------------------------------|-------------|
| `Id`                             | Identifiant unique représentant un couple `(Store, Date)` dans `test.csv` |
| `Store`                          | ID unique pour chaque magasin |
| `Sales`                          | Montant des ventes journalières (cible à prédire) |
| `Customers`                      | Nombre de clients un jour donné |
| `Open`                           | Indique si le magasin est ouvert (`1`) ou fermé (`0`) |
| `StateHoliday`                   | Jours fériés : `a` = férié officiel, `b` = Pâques, `c` = Noël, `0` = aucun |
| `SchoolHoliday`                  | Fermeture des écoles publiques (impact possible sur les ventes) |
| `StoreType`                      | Type de magasin : `a`, `b`, `c` ou `d` |
| `Assortment`                     | Niveau d'assortiment : `a` = basique, `b` = extra, `c` = étendu |
| `CompetitionDistance`           | Distance en mètres jusqu’au magasin concurrent le plus proche |
| `CompetitionOpenSinceMonth`     | Mois d’ouverture du concurrent |
| `CompetitionOpenSinceYear`      | Année d’ouverture du concurrent |
| `Promo`                          | Promo ponctuelle en cours (`1` = oui, `0` = non) |
| `Promo2`                         | Promo continue (`1` = oui, `0` = non) |
| `Promo2SinceYear`               | Année de début de participation à la Promo2 |
| `Promo2SinceWeek`               | Semaine calendaire de début de la Promo2 |
| `PromoInterval`                 | Mois où la Promo2 recommence : ex. `"Feb,May,Aug,Nov"` |


📌 **Remarques :**  
- Certains magasins ont été temporairement fermés pour rénovation.
- Les ventes (`Sales`) doivent être prédites uniquement pour les magasins ouverts (`Open = 1`) dans le jeu de test.


Ce jeu est utilisé pour explorer, visualiser et prédire les tendances commerciales.

## 📊 Outils utilisés

Python (pandas, seaborn, matplotlib, plotly)

scikit-learn (modèles de prédiction)

Power BI (tableau de bord interactif)

## Méthodologie

Nettoyage et transformation des données

Visualisation dynamique

Mesures d’évaluation : RMSE, MAE

##📌 Statut du projet

En cours de développement 

👤 Auteur

Marie Justine Ntsogo

##💡 Prochaines étapes

Ajouter un modèle de prédiction

Publier un tableau de bord Power BI

Merci de visiter ce dépôt ! 😊
