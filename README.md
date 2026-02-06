# Prédiction des salaires des développeurs

## Résumé
Dans ce projet, j’ai construit un modèle de machine learning pour prédire les salaires des développeurs à partir de données d’enquête.

- J’ai nettoyé et préparé des données à grande échelle en gérant les valeurs manquantes et les valeurs aberrantes.  
- J’ai créé de nouvelles variables à partir de colonnes multi-choix et encodé les variables catégorielles.  
- J’ai réduit la multicolinéarité et sélectionné des variables pertinentes pour la modélisation.  
- J’ai entraîné un modèle de régression linéaire et évalué ses performances selon différentes tranches de salaire.  
- J’ai analysé l’impact des compétences, des rôles et des caractéristiques des entreprises sur les salaires.  
Ce projet m’a permis de mieux comprendre toutes les étapes d’un projet de data science, du prétraitement des données à l’interprétation des résultats.

## Prochaines étapes
- Tester des modèles non linéaires comme Random Forest ou Gradient Boosting afin de capturer des relations plus complexes et mieux prédire les hauts salaires.  
- Créer des variables d’interaction, par exemple en combinant des compétences et des rôles (ex. : Python × Data Scientist), pour analyser l’impact de certaines combinaisons.  
- Expérimenter avec différentes décisions sur les données : supprimer le plafond de salaire, utiliser l’imputation au lieu de supprimer les valeurs manquantes, ou ajouter des informations géographiques plus précises (ville/région plutôt que pays).  
- Concevoir des supports adaptés aux utilisateurs : guide compétences-salaire pour les apprenants, tableau de bord géographique pour les recruteurs, ou rapport « facteurs contrôlables vs fixes » pour l’orientation de carrière.  
- Rendre le projet prêt pour un portfolio en améliorant l’analyse, la documentation et en mettant en avant les résultats les plus pertinents.  

Ces améliorations permettront d’augmenter la qualité du modèle et la valeur pratique du projet.

---

## Dataset

Le dataset utilisé n'est pas fourni mais peut être retrouvé à l'adresse suivante :
https://app.dataquest.io/m/950/predicting-developer-salaries%3A-a-machine-learning-analysis-of-stack-overflow-survey-data/1/explore-the-raw-survey

---
## Technologies et installation

**Technologies utilisées :** Python, scikit-learn, matplotlib, seaborn, LinearRegression, train_test_split

**Instructions pour reproduire le projet :**
1. Cloner le dépôt : `git clone https://github.com/Sami-Bo/predicting_dev_salaries.git`
2. Installer les librairies nécessaires : `pip install scikit-learn matplotlib seaborn`
3. Ouvrir le notebook : `Jupyter Notebook` ou `VS Code`
4. Exécuter les cellules dans l’ordre pour reproduire l’analyse et les visualisations
