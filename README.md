# Télécom Churn Prediction

Ce projet contient un notebook de datamining pour la prédiction du churn client dans le secteur des télécoms.

## Contenu

- `Churn_Prediction_DataMining.ipynb` : Notebook principal pour l'exploration des données, le prétraitement, la construction du modèle, et l'évaluation.
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` : Jeu de données client utilisé pour l'entraînement et l'évaluation.

## Objectif

Ce projet vise à :

- analyser le comportement client
- construire des modèles de classification du churn
- comparer plusieurs algorithmes
- visualiser les performances avec ROC, matrice de confusion et autres métriques

## Installation

1. Ouvrez un terminal dans le dossier `projetdatamining`
2. Créez un environnement virtuel Python (recommandé) :

```bash
python -m venv venv
```

3. Activez l'environnement :

```powershell
# Windows PowerShell
.\venv\Scripts\Activate.ps1
```

4. Installez les dépendances :

```bash
pip install -r requirements.txt
```

## Exécution

Lancez le notebook avec Jupyter :

```bash
jupyter notebook
```

Puis ouvrez `Churn_Prediction_DataMining.ipynb`.

## Dépendances principales

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- xgboost
- notebook

## GitHub

Pour pousser le projet sur GitHub :

```bash
git init
git add .
git commit -m "Ajout du notebook de churn et des fichiers de configuration"
git branch -M main
git remote add origin https://github.com/<votre-utilisateur>/<votre-repo>.git
git push -u origin main
```

Remplacez `<votre-utilisateur>` et `<votre-repo>` par vos informations GitHub.
