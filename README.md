# Télécom Churn Prediction

Ce projet contient un notebook de datamining pour la prédiction du churn client dans le secteur des télécoms.

## Contenu

- `code_projet.ipynb` : Notebook principal pour l'exploration des données, le prétraitement, la construction du modèle, et l'évaluation.
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

Puis ouvrez `code_projet.ipynb`.

## Dépendances principales

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- xgboost
- notebook
