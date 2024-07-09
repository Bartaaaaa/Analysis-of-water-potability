# SY09 - P24 - Projet de groupe 

## Introduction
Ce projet a été réalisé dans le cadre de l'uv SY09 de la formation d'ingénieur de l'UTC.
L'objectif est de prendre en main un dataset pour lui appliquer des méthodes (visualisation, classification, régression, ... ) 
pour prédire et classer la potabilité de l'eau en utilisant le dataset [Water Potability](https://www.kaggle.com/datasets/gauravduttakiit/water-potability-prediction) disponible sur Kaggle.

## Dataset
Récapitulatif des colonnes de notre dataset afin d'en comprendre les notions associées

- **pH** : Mesure de l'acidité ou de l'alcalinité de l'eau sur une échelle de 0 à 14. Un pH de 7 est neutre, les valeurs inférieures à 7 indiquent une acidité, et celles supérieures à 7 une alcalinité.

- **Dureté** : Indique la capacité de l'eau à précipiter le savon, mesurée en milligrammes par litre (mg/L). Elle est principalement déterminée par la concentration des sels de calcium et de magnésium.

- **Solides** : Représente la totalité des solides dissous dans l'eau, mesurée en parties par million (ppm). Cela inclut les minéraux, les sels et les matières organiques.

- **Chloramines** : Mesure la quantité de chloramines présentes dans l'eau, en parties par million (ppm). Les chloramines sont des désinfectants utilisés pour traiter l'eau potable.

- **Sulfate** : Indique la concentration de sulfates dissous dans l'eau, mesurée en milligrammes par litre (mg/L). Les sulfates sont des substances qui peuvent se trouver naturellement dans les minéraux.

- **Conductivité** : Réfère à la conductivité électrique de l'eau, mesurée en microsiemens par centimètre (μS/cm). C'est un indicateur de la quantité d'ions présents dans l'eau.

- **Carbone Organique** : Mesure la quantité de carbone organique trouvée dans l'eau, en parties par million (ppm). Il sert d'indicateur de la qualité de l'eau.

- **Trihalométhanes** : Composés chimiques présents dans l'eau, mesurés en microgrammes par litre (μg/L). Ils sont formés comme sous-produit de la chloration.

- **Turbidité** : Mesure de la turbidité ou de la limpidité de l'eau, indiquée en Unités Néphélométriques de Turbidité (NTU). Cela est causé par des particules généralement invisibles à l'œil nu.

- **Potabilité** : Indicateur binaire montrant si l'eau est potable pour la consommation humaine. Une valeur de 1 signifie potable (sûre à boire), et une valeur de 0 signifie non potable (non sûre à boire).


## Objectifs
Les objectifs spécifiques de ce projet sont les suivants :
- Explorer et analyser le dataset pour en comprendre la structure et les caractéristiques.
- Effectuer un prétraitement des données pour nettoyer, transformer et préparer les données pour la modélisation.

## Technologies Utilisées
- Python
- Jupyter Notebook
- Bibliothèques Python : Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, etc.

## Structure du Projet
Le projet est organisé comme suit :
- **Visualisation** : Ces notebooks permettent de visualiser les données de notre df afin de tirer de premières conclusions
- **Analyse** : Ces notebooks permettent d'appliquer des méthodes d'analyse de datascience sur notre dataset
- **Rapport** : Un rapport résumant les résultats, les conclusions et les insights tirés du projet (rédigé en LaTeX).

## Installation
Pour exécuter les notebooks, assurez-vous d'avoir Python et Jupyter Notebook installés. Vous pouvez installer les dépendances requises en exécutant la commande suivante dans votre terminal :
- git clone <URL_du_dépôt>
- cd nom_du_projet
- virtualenv venv
- source venv/bin/activate (ou venv\Scripts\activate pour Windows)
- **pip install -r requirements.txt**

Ces opérations ne sont pas forcément nécessaires en fonction de l'IDE (environnement créé automatiquement)

## Contributeurs
- Victor Demessance
- Bartlomiej Grzadziel
- Elsa Strassia
