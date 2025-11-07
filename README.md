# Space-Titinac-machine-learning-project

This project is based on the Spaceship Titanic competition
on Kaggle. The goal is to predict whether a passenger of the Spaceship Titanic was transported to another dimension after an incident.


Ce projet est basé sur la compétition Spaceship Titanic
sur Kaggle. Le but est de prédire si un passager du vaisseau spatial Titanic a été transporté vers une autre dimension après un incident.

This project demonstrates my skills in data cleaning, feature engineering, modeling, and evaluation of Machine Learning models, while following a professional workflow to solve real-world problems.

Ce projet permet de démontrer mes compétences en nettoyage de données, création de nouvelles features, modélisation et évaluation de modèles de Machine Learning, tout en appliquant une méthodologie professionnelle et surtout faire comprendre aux recruteurs qui passeront sur mon compte de quoi je suis capable.

It also shows that I can perform well using a single model without any data leakage.

Il montre également que je peux obtenir d’excellents résultats avec un seul modèle, sans aucune fuite de données.

Objectives / Objectifs

Explore and understand the dataset (EDA)

Clean and prepare data for modeling (handle missing values intelligently or with an “unknown” category, encode categorical variables properly)

Build, compare, and optimize Machine Learning models (RandomForest, Gradient Boosting, LightGBM, XGBoost)

Present clear and reproducible results

Demonstrate the impact of feature selection and algorithm choice on model performance (using Mutual Information, Seaborn visualization, and permutation importance)

 (VF)
Explorer et comprendre les données (EDA)

Nettoyer et préparer les données pour la modélisation (gestion intelligente des valeurs manquantes ou création d’une catégorie “unknown”, encodage adapté des variables catégorielles)

L'utilisation d'un seul modèle pour performer efficacement

Présenter des résultats clairs et reproductibles

Montrer l’impact du choix des features et des algorithmes sur la performance du modèle (Mutual Information, visualisation Seaborn, permutation importance)

Technologies and Libraries / Technologies et Librairies

Python 3

Pandas / NumPy – data manipulation / manipulation de données

Scikit-learn – modeling and pipelines / modélisation et pipelines

Matplotlib / Seaborn – visualization 

SHAP – explainability / interprétabilité

LightGBM   machine learning models


 Methodology / Méthodologie
1. Exploratory Data Analysis (EDA) / Analyse exploratoire

Count dataset rows and columns / Comptage des lignes et colonnes

Find the topic of each data / Comprendre le thème et la logique derrière les jeux de donnée

Detect rare categories that may bias MI / Détection des catégories rares qui peuvent biaiser le MI

Identify string columns to create new features / Identification des colonnes à découper en nouvelles features


2. Data Preprocessing / Prétraitement des données

Handle missing values intelligently / Gestion intelligente des valeurs manquantes

Encode categorical variables according to their type (nominal/ordinal)(to add in  this model) / Encodage des variables catégorielles selon leur nature (nominale ou ordinale)(à  ajouter dans ce modèle)

3. Feature Selection / Sélection de Features

Use Mutual Information (MI) to test dependency between features and target / Utilisation du MI de manière innovantes  pour tester la dépendance entre les features  et la cible

Use MI to test dependency between features themselves / Utilisation du MI pour détecter les redondances entre colonnes

Remove redundant features / Suppression des colonnes fortement dependantes 

Create new engineered features based on logic and MI results / Création de nouvelles features à partir de ma logique et des résultats du MI 

Evaluate importance via permutation and model-based ranking / Évaluation de l’importance via permutation et modèles de base

4. Modeling / Modélisation

I used LightGBM as my main model to focus on advanced feature engineering and faster iterations.
J’ai utilisé LightGBM comme modèle principal afin de concentrer mon travail sur le feature engineering et de réduire le temps d’expérimentation.

I applied Optuna for hyperparameter tuning, and used Stratified K-Fold cross-validation to ensure balanced class splits and better generalization.

J’ai utilisé Optuna pour l’optimisation des hyperparamètres et Stratified K-Fold pour assurer une meilleure généralisation du modèle.

5. Evaluation / Évaluation

Metric: Accuracy

Cross-validation: Stratified K-Fold

 (VF)
Metric : Accuracy

Validation croisée : Stratified K-Fold



Results / Résultats

used model: LightGBM

Best Kaggle score: 0.80734 accuracy

Most important features:  "CryoSleep","deckhome" ,TotalSpend etc..

Modèle utilisé : LightGBM

Meilleur score Kaggle : 0,80734 accuracy

Features les plus importantes : "CryoSleep","deckhome" ,TotalSpend etc..

 CodeSpace

You can explore my notebook to see how I explain each choice and step of my workflow.
Vous pouvez consulter mon notebook pour voir comment j’explique chacun de mes choix et ma manière de travailler.Il se trouve dans le fichier space_titanic_CodeSpace

🧩 Conclusion / Conclusion

This project highlights my ability to:

Structure an end-to-end Machine Learning workflow

Handle missing values and categorical variables effectively

Build and evaluate performant ML models

Communicate results clearly and professionally

Ce projet met en avant ma capacité à :

Structurer un projet Machine Learning de bout en bout

Gérer les données manquantes et catégorielles avec logique et rigueur

Construire et évaluer des modèles performants

Communiquer mes résultats de manière claire et professionnelle

I’m aware that I still have a lot to learn, but I improve every day and constantly do research to push my limits. If this project doesn’t yet meet your expectations for a paid internship, I invite you to look at my House Price Advanced project (ranked 61/5394 without data leakage), where I implemented specific encodings for each type of feature, target encoding for high-cardinality variables, redundancy management, and skewness correction.If after that ,you want see more ,like I love challenges and competition feel free to test me.

(VF)
Je suis conscient qu’il me reste encore  des choses à apprendre , c'est pour cette raison que je suis ouvert à toutes les propositions professionnelles (Stage remunéré ,internship, job junior en ML, data scientit, research IA... ).Tant que vous permettez de continuer mes recherches   de manière approfondi et aussi me nourrir  je suis à l'écoute.  Si ce projet n’atteint pas encore vos attentes ,  je vous invite à regarder mon projet House Price Advanced (61ᵉ/5394 sans fuite de données), où j’ai mis en place des encodages spécifiques, un target encoding pour les variables à forte cardinalité, une gestion des redondances et une correction des skewness.
Et si après ça vous n'êtes pas convaincu de mon talent ,comme J’aime les défis et la compétition n’hésitez pas à me challenger.


