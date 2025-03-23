# Projet de Machine Learning : Prédiction de la Qualité des Vins

Ce projet vise à prédire la qualité des vins rouges et blancs à l'aide de modèles de machine learning. Le projet inclut une analyse exploratoire des données, une phase de prétraitement, la mise en œuvre de différents modèles, et l'évaluation de leurs performances.

## Données

Les ensembles de données utilisés proviennent de fichiers CSV :
- `winequality-red.csv` : Données sur les vins rouges.
- `winequality-white.csv` : Données sur les vins blancs.

### Contenu des données
Chaque ensemble de données contient plusieurs caractéristiques physiques et chimiques (comme l'acidité, le pH, le taux d'alcool, etc.) ainsi qu'une étiquette de qualité (score).

## Objectif
L'objectif principal est de développer un modèle capable de déterminer les facteurs qui influencent la qualité des vins à partir de leurs caractéristiques.

## Outils et Bibliothèques
- **Manipulation des données** : pandas, numpy
- **Visualisation** : matplotlib, seaborn
- **Machine Learning** : scikit-learn
  - Modèles :
    - Régression linéaire
    - Support Vector Regression (SVR)
    - Random Forest Regressor
  - Prétraitement : StandardScaler
  - Évaluation : Cross-validation (StratifiedKFold), Root Mean Squared Error (RMSE)

## Structure du Projet
1. **Analyse exploratoire des données** :
   - Inspection des données (valeurs manquantes, distributions, etc.).
   - Visualisation des relations entre les caractéristiques et la qualité.

2. **Prétraitement des données** :
   - Normalisation des variables.
   - Séparation des ensembles d'entraînement et de test.

3. **Modélisation** :
   - Entraînement de différents modèles.
   - Comparaison des performances à l'aide de RMSE.

4. **Évaluation** :
   - Analyse des résultats.
   - Identification du modèle offrant les meilleures prédictions.

## Instructions pour Exécuter le Projet

### Prérequis
- Python 3.8 ou version supérieure
- Bibliothèques : pandas, numpy, matplotlib, seaborn, scikit-learn

### Exécution
1. Clonez le répertoire :
   ```bash
   git clone <URL_du_répertoire>
   ```
2. Accédez au répertoire :
   ```bash
   cd <nom_du_répertoire>
   ```
3. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
   ```
4. Lancez le notebook :
   ```bash
   jupyter notebook model_vin.ipynb
   ```

## Résultats
Le modèle Random Forest a montré les meilleures performances sur l'ensemble de test. On voit que le taux d'alcool est le facteur le plus impactant sur la qualité du vin.

## Contributions
Les contributions sont les bienvenues. Pour contribuer :
1. Forkez le projet.
2. Créez une nouvelle branche :
   ```bash
   git checkout -b feature/nom_de_votre_feature
   ```
3. Soumettez une pull request.

## Licence
Ce projet est sous licence MIT. Vous êtes libre de l'utiliser et de le modifier.

