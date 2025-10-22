# 🚢 Titanic Survival Prediction

> Projet Data Science – Prédiction de la survie des passagers du Titanic à partir de leurs caractéristiques démographiques et socio-économiques.

---

## 🎯 Objectif du projet
L’objectif de ce projet est de **prédire la probabilité de survie des passagers** du Titanic à l’aide d’algorithmes de machine learning.  
C’est un projet d’initiation classique à la data science, basé sur le célèbre concours **Kaggle – Titanic: Machine Learning from Disaster**.

---

## 🧠 Démarche Data Science

### 1. **Exploration des données**
- Analyse des variables et traitement des valeurs manquantes  
- Visualisation des corrélations (âge, classe, sexe, tarif, etc.)  
- Étude des distributions et relations avec la variable cible `Survived`

### 2. **Préparation des données**
- Encodage des variables catégorielles  
- Normalisation et sélection des features  
- Création d’un ensemble d’entraînement et de validation

### 3. **Modélisation**
- Régression Logistique  
- Random Forest  
- XGBoost  
- Comparaison des performances (Accuracy, F1-score)

### 4. **Évaluation et interprétation**
- Analyse des erreurs de prédiction  
- Visualisation de l’importance des variables  
- Génération d’un fichier `submission.csv` pour Kaggle

---

## 📊 Résultats obtenus
Le modèle **Random Forest** a atteint une **accuracy d’environ 82 %** sur l’ensemble de validation.  
Les variables les plus influentes : `Sex`, `Pclass`, `Age` et `Fare`.

---

## 🛠️ Outils et technologies
- **Langage :** Python  
- **Bibliothèques :** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost  
- **Environnement :** Jupyter Notebook  
- **Source des données :** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)

---

## 🚀 Améliorations futures
- Optimisation d’hyperparamètres avec GridSearchCV  
- Feature engineering avancé (titres, familles, ponts d’embarquement, etc.)  
- Utilisation de modèles d’ensemble (Stacking, VotingClassifier)  
- Déploiement du modèle via Streamlit  

---

## 👤 À propos de moi
Je suis **[Ton Nom]**, data scientist passionné par la donnée et son potentiel à créer de la valeur.  
Mon objectif est de **transformer les données en décisions stratégiques** grâce à l’analyse, la modélisation et la visualisation.  

📫 [ton.email@example.com]  
🔗 [LinkedIn](https://linkedin.com/in/tonprofil)  
💻 [Portfolio](https://tonpseudo.github.io/)

---

### 🧾 Licence
Ce projet est sous licence MIT.  
Vous pouvez librement le consulter, le cloner et l’adapter à vos besoins à des fins éducatives.
