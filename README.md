# Diabetes Prediction — SVM

Notebook Jupyter de classification binaire : prédit si une personne est diabétique à partir de mesures médicales (grossesses, glucose, pression artérielle, épaisseur cutanée, insuline, IMC, hérédité, âge), en utilisant le dataset Pima Indians Diabetes.

## Approche

1. Chargement et exploration du dataset (`diabetes.csv`)
2. Normalisation des features avec `StandardScaler`
3. Séparation train/test stratifiée
4. Entraînement d'un **SVM à noyau linéaire** (`sklearn.svm.SVC`)
5. Évaluation : ~78,7 % de précision sur l'entraînement, ~77,3 % sur le test
6. Exemple de prédiction sur une nouvelle entrée

## Tech stack

- **pandas**, **numpy** — manipulation de données
- **scikit-learn** — `StandardScaler`, `train_test_split`, `svm.SVC`, `accuracy_score`

## Lancer le projet

```bash
pip install numpy pandas scikit-learn jupyter
jupyter notebook Untitled10.ipynb
```

Nécessite le fichier `diabetes.csv` (dataset Pima Indians Diabetes) dans le même dossier.
