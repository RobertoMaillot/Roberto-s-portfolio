# Projet 3 : Prédiction de la durée de la carrière des joueurs de NBA 🏀

## Introduction :
Dans le cadre de mon master et plus précisément de mon cours de Big data, j'ai réalisé un projet complet visant à prédire la durée de carrière des basketteurs professionnels. Ce projet illustre mes compétences en collecte de données, nettoyage, modélisation prédictive et communication des résultats.

## Objectif 🎯 :
L'objectif principal de ce projet était de développer un modèle prédictif capable de déterminer si un joueur de basket-ball aura une carrière professionnelle de plus de cinq ans. En utilisant des données historiques sur les performances des joueurs, des caractéristiques individuelles et des statistiques de match, j'ai entraîné plusieurs modèles et évalué leur performance pour prédire le succès futur des joueurs.

## Étapes du Projet ⛰️ :

### Collecte de Données :
- Collecte de données sur les carrières des joueurs via Kaggle
- Importation sur JupyterLab

<img width="701" alt="Capture d’écran 2024-03-25 à 15 30 02" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/ce1c3d4b-cc3e-4cfe-9d43-494f0c2f8939">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 29 25" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/401b846d-b18b-440b-9828-7d5b4d43e030">

### Exploration des Données :
- Analyse exploratoire pour comprendre les tendances et les relations entre les variables.
- Visualisation des données pour identifier les caractéristiques importantes des joueurs à prendre en compte dans la modélisation.
python

<img width="270" alt="RangeIndex 1340 entries," src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/6764f66c-625c-4416-9bc2-8993b710525e">

### Traitement de la donnée:
- Séparation en base Train et base test
- Traitement et remplacement des valeurs nulls
- Standardisation de la données (features = variables numériques) 
- MinMaxScaler() & fit_transform()

<img width="701" alt="Capture d’écran 2024-03-25 à 15 30 34" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/5986485e-73d8-4279-b980-c5d0eb4efb58">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 31 15" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/bbd2f1ec-b6d5-4d29-bafa-63c1d4daac36">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 31 40" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/ec6d3079-8eae-401f-a413-f5f0d26804b5">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 32 16" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/ce7ac7da-cc84-428e-bd5d-e4f66e6af5e5">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 32 55" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/9e3ae736-9d4b-483d-ba7b-14fbae4e34b0">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 35 00" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/d79c9f34-899d-4cca-9561-05a46b2d5c91">

### Modélisation Prédictive :
- Mise en place d’une fonction pour mesurer la performance des différents modèles
- Entraînement de plusieurs modèles de machine learning, y compris Modèle de Régression Logistique, Random Forest et LightGBM, Arbre de décision, SVM pour prédire la durée de carrière des joueurs.

<img width="701" alt="Capture d’écran 2024-03-24 à 10 51 58" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/e42ef7b6-39f3-4d69-be10-4c0b56d418e2">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 36 07" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/01b84eba-ef10-432e-8a3f-75439bbbf82b">
<img width="701" alt="ROC CURVE IN TEST DATA BASE" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/ac065e15-1ea5-4aec-be22-7cf6d45eec53">
<img width="701" alt="Capture d’écran 2024-03-24 à 11 00 31" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/e48bcc2a-bc76-495d-a041-378945a5f553">


### Analyse des Résultats :
- Comparaison des performances des différents modèles pour sélectionner le meilleur modèle.
- Évaluation des modèles en utilisant des métriques telles que l'AUC, le taux de succès et le taux d'erreur.

<img width="701" alt="Capture d’écran 2024-03-24 à 10 51 58" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/5c2699b3-1a7e-4824-b99c-c154dc9199ff">
<img width="701" alt="Capture d’écran 2024-03-25 à 15 36 07" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/d842698a-ac41-4338-996b-1b2bccb60d50">
<img width="701" alt="ROC CURVE IN TEST DATA BASE" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/6994aa05-dd3a-4f11-aca8-732314f8baa3">
<img width="701" alt="Capture d’écran 2024-03-24 à 11 00 31" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/c2f528c8-61cc-49b1-ad14-099c3c588276">

## Prédiction  :
- Prédiction de la durée de carrière des joueurs actuels et présentation des résultats.
- Sélection du modèle le plus performant pour prédire la durée de carrière des joueurs.

<img width="893" alt="Capture d’écran 2024-03-24 à 11 01 58" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/785d4a01-e53d-4de3-8f5f-be0275177747">
<img width="831" alt="Capture d’écran 2024-03-24 à 11 02 27" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/7fb1077a-dd9d-4943-9a74-41036a2598ed">
<img width="576" alt="Capture d’écran 2024-03-24 à 11 03 07" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/50adbd06-5551-4745-ac37-9d16e6010353">
<img width="851" alt="Capture d’écran 2024-03-24 à 11 03 44" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/12cd1760-35c7-4526-be0a-4a15691467cf">
<img width="640" alt="Capture d’écran 2024-03-24 à 11 05 05" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/5cfecedd-b62f-4a7e-a8fb-12934167301a">
<img width="778" alt="Capture d’écran 2024-03-24 à 11 05 50" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/114fedb2-787f-4428-a8c3-fd6141fc946b">
<img width="566" alt="Capture d’écran 2024-03-24 à 11 06 22" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/2738c082-0a06-4cbf-aa36-521bca7a8ff8">
<img width="834" alt="Capture d’écran 2024-03-24 à 11 07 10" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/fbc9d990-9378-4967-a9c9-00fd0e7acf13">

## Compétences Techniques Acquises :
✅Collecte et nettoyage de données
✅Exploration des données pour identifier des tendances et des caractéristiques importantes.
✅Modélisation prédictive avec des techniques avancées de Machine Learning.
✅Évaluation et interprétation des modèles pour prendre des décisions éclairées.
✅Communication des résultats 

## Conclusion 📊 :
Ce projet met en lumière mes compétences en Data Analyse et en modélisation prédictive, ainsi que ma capacité à résoudre des problèmes réels en utilisant des techniques avancées d'apprentissage automatique. En déterminant les facteurs clés qui influent sur la durée de carrière des joueurs de basket-ball, ce projet offre des informations précieuses pour les équipes et les recruteurs dans le domaine du sport professionnel.
