# Space-Titinac-machine-learning-project

#English version
##  Context

This project is based on the **[Spaceship Titanic competition](https://www.kaggle.com/competitions/spaceship-titanic)** on Kaggle.  
The goal is to predict whether a passenger of the Spaceship Titanic was **transported to another dimension** after an incident.

This project demonstrates my skills in **data cleaning, feature engineering, modeling, and evaluation of Machine Learning models**, while applying a professional workflow to solve real-world problems.



##  Objectives

- Explore and understand the dataset (EDA)  
- Clean and prepare the data for modeling (handling missing values through intelligent imputation or with an "unknown" category, categorical encoding)  
- Build, compare, and optimize multiple Machine Learning models (RandomForestClassifier, Gradient Boosting, LightGBM, XGBoost)  
- Present clear and reproducible results  
- Demonstrate the impact of feature selection and algorithm choice on model performance (using Mutual Information, Seaborn visualization, and permutation importance)  



##  Technologies and Libraries

- **Python 3**  
- **Pandas / NumPy** – data manipulation  
- **Scikit-learn** – modeling and pipelines  
- **Matplotlib / Seaborn** – visualization  
- **XGBoost / LightGBM / RandomForestClassifier**  



##  Methodology

1. **Exploratory Data Analysis (EDA)**  
   - Count rows and columns of the dataset  
   - Check categories and values for each column  
   - Detect rare categories that could bias MI due to high variance  
   - Identify string columns that could be split into new features  

2. **Data Preprocessing**  
   - Handle missing values (not necessary for MI, but required for encoding)  
   - Encode categorical variables  

3. **Feature Selection**  
   - Use Mutual Information to test dependency between features and the target  
   - Use MI to test dependency between features themselves  
   - Remove redundant features with high MI correlation  
   - Create new features (feature engineering) and re-check MI with the target  
   - Apply permutation importance on engineered features and baselines  

4. **Modeling**  
   - Random Forest, Gradient Boosting, LightGBM  
   - Manual hyperparameter optimization (to be improved in future work)  

5. **Evaluation**  
   - Metrics: Accuracy / F1-Score  
   - Model comparison (limited locally due to computation time, most tests done directly on Kaggle)  



##  Results

- Best model: **LightGBM**  
- Best Kaggle score: **0.80687 accuracy**  
- Most important categorical features:  
  `"HomePlanet"`, `"CryoSleep"`, `"Destination"`, `"VIP"`, `"deckhome"`, `"side"`, `"group"`, `"deck"`


## Useful Links

- Kaggle Notebook: [My Kaggle submission](https://www.kaggle.com/code/angegabrielilisyvain/suppresion-de-la-colonne-group?scriptVersionId=265028721)  



## Conclusion

This project highlights my ability to:  
- Structure an end-to-end Machine Learning workflow  
- Handle missing values and categorical variables effectively  
- Build and evaluate performant ML models  
- Communicate results in a clear and professional way  

It represents a strong example of a **Machine Learning workflow suitable for a junior position in data science, data analysis, or machine learning**.  




#French version 
##  Contexte

Ce projet est basé sur la compétition **[Spaceship Titanic]([https://www.kaggle.com/competitions/spaceship-titanic]** sur Kaggle.  
Le but est de prédire si un passager du vaisseau spatial Titanic a été **transporté vers une autre dimension** suite à un incident.

Ce projet permet de démontrer mes compétences en **data cleaning, feature engineering, modélisation et évaluation de modèles de Machine Learning**, tout en appliquant un workflow professionnel pour la résolution de problèmes réels.

##  Objectifs

- Comprendre et explorer les données (EDA)  

- Nettoyer et préparer les données pour la modélisation (gestion des valeurs manquantes par imputation intelligente ou par une variable unknown, encodage des variables catégorielles,)  

- Construire, comparer et optimiser plusieurs modèles de Machine Learning(RandomForestClassif,les gradiants boostings)  

- Présenter des résultats clairs et reproductibles  

- Démontrer l’impact des choix de features et d’algorithmes sur la performance du modèle (Par une utilisation du MI , de la visualisation seaborn , par des permutations par importance)

##  Technologies et Librairies

- **Python 3**  
- **Pandas / NumPy** – manipulation de données  
- **Scikit-learn** – modélisation et pipelines  
- **Matplotlib / Seaborn** – visualisations  
- **XGBoost / LightGBM**/**RandomForestclassif**

- ##  Méthodologie

1. **Analyse Exploratoire (EDA)**

   -Comptages du nombres de lignes et de colonnes du dataframe 

   -Comptage des catégories et valeurs de chaques colonnes

   -Comptage des catégories et valeurs  qui se répètent une seule fois pour           savoir quelle colonnes pourront avoir un MI biasé à cause d'une variance  de      valeurs ou de catégories trop elévé

   -Recherhce des colonnes de types strings pour pouvoir potentiellement les          séparées
   
   
  

3. **Prétraitement des données**  
  -  Gestion des valeurs manquantes(pas nécessaire pour faire  le MI, mais              nécessaire   pour l'encodage )
  - Encodage des variables catégorielles  
   
3. **Sélection de Features**  
   - Mutual information
   
   -Utilisation du MI pour tester la dépendances des colonnes par rapport au           target

   -Utilisation du MI pour tester la dépendandce des colonnes entre elles

   -Piochage des colonnes avec un fort MI entre elles afin d'éviter les                redondances pour mon modèle

   -Créations de fetures engineering à partir de ces colonnes,vérifications par        mon MI à nouveau de la dépendance par rapport au target de celles-ci


   -Permutaion par importance du feature engineering, et des features qui le           compose pour savoir quel assemblage apporte le mieux d'information à mon           modèle 

   - Importance des features via modèles baselines
  
  
5. **Modélisation**  
   - Random Forest, Gradient Boosting  
   - Optimisation des hyperparamètres manuel(mais c'était une perte de temps ,je       vais améliorer ça)  

6. **Évaluation**  
   - Accuracy / F1-Score  
   - Comparaison des modèles sur validation et test (impossible sur mon ordinateur     , temps de résultat trop long donc je faisais directement sur kaggle )
  
     ## Résultats

- Meilleur modèle : **Lightgbm**  
- Meilleur score Kaggle : **0,80687% accuracy**  
- Visualisation des features  object les plus importantes :
  "HomePlanet","CryoSleep","Destination","VIP","deckhome","side","group","deck" 

   ##  Liens utiles
  > Pour plus de détails sur les notebooks et les soumissions, voir mon compte       kaggle **[(https://www.kaggle.com/code/angegabrielilisyvain/suppresion-de-la-colonne-group?scriptVersionId=265028721))**]

#  Conclusion

Ce projet montre ma capacité à :  
- Structurer un projet de A à Z  
- Gérer les données manquantes et catégorielles  
- Construire et évaluer des modèles ML performants  
- Communiquer les résultats de manière claire et professionnelle  

Il constitue un excellent exemple de **workflow Machine Learning pour un poste junior en data science/data analyst / machine learning**.
