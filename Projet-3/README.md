# Projet 3 : Prédiction de la durée de la carrière des joueurs de NBA 🏀

## Introduction :
Dans le cadre de mon master et plus précisément de mon cours de Big data, j'ai réalisé un projet complet visant à prédire la durée de carrière des basketteurs professionnels. Ce projet illustre mes compétences en collecte de données, nettoyage, modélisation prédictive et communication des résultats.

## Objectif 🎯 :
L'objectif principal de ce projet était de développer un modèle prédictif capable de déterminer si un joueur de basket-ball aura une carrière professionnelle de plus de cinq ans. En utilisant des données historiques sur les performances des joueurs, des caractéristiques individuelles et des statistiques de match, j'ai entraîné plusieurs modèles et évalué leur performance pour prédire le succès futur des joueurs.

## Étapes du Projet ⛰️ :

### Collecte de Données :
- Collecte de données sur les carrières des joueurs via Kaggle
- Importation sur JupyterLab

<picture>
<img width="701" alt="Capture d’écran 2024-03-25 à 15 30 02" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/ce1c3d4b-cc3e-4cfe-9d43-494f0c2f8939">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 29 25" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/401b846d-b18b-440b-9828-7d5b4d43e030">
</picture>

### Exploration des Données :
- Analyse exploratoire pour comprendre les tendances et les relations entre les variables.
- Visualisation des données pour identifier les caractéristiques importantes des joueurs à prendre en compte dans la modélisation.
python

<picture>
<img width="270" alt="RangeIndex 1340 entries," src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/6764f66c-625c-4416-9bc2-8993b710525e">
</picture>

### Traitement de la donnée:
- Séparation en base Train et base test
- Traitement et remplacement des valeurs nulls
- Standardisation de la données (features = variables numériques) 
- MinMaxScaler() & fit_transform()

<picture>
<img width="701" alt="Capture d’écran 2024-03-25 à 15 30 34" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/5986485e-73d8-4279-b980-c5d0eb4efb58">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 31 15" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/bbd2f1ec-b6d5-4d29-bafa-63c1d4daac36">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 31 40" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/ec6d3079-8eae-401f-a413-f5f0d26804b5">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 32 16" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/ce7ac7da-cc84-428e-bd5d-e4f66e6af5e5">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 32 55" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/9e3ae736-9d4b-483d-ba7b-14fbae4e34b0">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 35 00" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/d79c9f34-899d-4cca-9561-05a46b2d5c91">
</picture>

### Modélisation Prédictive :
- Mise en place d’une fonction pour mesurer la performance des différents modèles
- Entraînement de plusieurs modèles de machine learning, y compris Modèle de Régression Logistique, Random Forest et LightGBM, Arbre de décision, SVM pour prédire la durée de carrière des joueurs.

<picture>
<img width="701" alt="Capture d’écran 2024-03-24 à 10 30 59" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/678fb1e6-ca99-465b-a504-b52f66e7038a">
<img width="701" alt="Capture d’écran 2024-03-24 à 10 34 53" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/fa45f203-cecb-4ff5-b083-426e498d037e">
<img width="701" alt="Capture d’écran 2024-03-24 à 10 39 05" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/222fb72b-c158-4626-9133-2a8262d41950">
<img width="701" alt="Capture d’écran 2024-03-24 à 10 51 34" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/b53c0a1a-8aab-43a9-8a75-5bc74f1b25ae">
</picture>

### Analyse des Résultats :
- Comparaison des performances des différents modèles pour sélectionner le meilleur modèle.
- Évaluation des modèles en utilisant des métriques telles que l'AUC, le taux de succès et le taux d'erreur.

<picture>
<img width="701" alt="Capture d’écran 2024-03-24 à 10 51 58" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/5c2699b3-1a7e-4824-b99c-c154dc9199ff">
<img width="431" alt="Capture d’écran 2024-03-25 à 15 36 07" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/9c9611ea-6738-4528-a2ac-49339f9169e0"> <img width="301" alt="ROC CURVE IN TEST DATA BASE" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/29531352-a060-4320-8d5c-202cf2f514c5">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 53 02" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/a9a1b3ea-b932-47b7-8c49-e88aa6c28f50">
</picture>

## Prédiction  :
- Prédiction de la durée de carrière des joueurs actuels et présentation des résultats.
- Sélection du modèle le plus performant pour prédire la durée de carrière des joueurs.

<picture>
<img width="701" alt="Capture d’écran 2024-03-24 à 11 01 58" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/ebffea68-3259-402e-923a-6cc4192bb175">
<img width="701" alt="Capture d’écran 2024-03-24 à 11 03 07" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/9be0cb60-c5b8-4b88-b844-21eeef050ede">
<img width="701" alt="Tony Dumas" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/3694f8ce-10d1-4102-b9b4-d9f82b93f15c">
</picture>

## Compétences Techniques Acquises :
✅Collecte et nettoyage de données

✅Exploration des données pour identifier des tendances et des caractéristiques importantes.

✅Modélisation prédictive avec des techniques avancées de Machine Learning.

✅Évaluation et interprétation des modèles pour prendre des décisions éclairées.

✅Communication des résultats 

## Conclusion 📊 :
Ce projet met en lumière mes compétences en Data Analyse et en modélisation prédictive, ainsi que ma capacité à résoudre des problèmes réels en utilisant des techniques avancées d'apprentissage automatique. En déterminant les facteurs clés qui influent sur la durée de carrière des joueurs de basket-ball, ce projet offre des informations précieuses pour les équipes et les recruteurs dans le domaine du sport professionnel.
