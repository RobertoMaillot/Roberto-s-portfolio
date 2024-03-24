# Projet 3 : Prédiction de la durée de la carrière des joueurs de NBA 🏀

## Introduction :
Dans le cadre de mon master et plus précisément de mon cours de Big data, j'ai réalisé un projet complet visant à prédire la durée de carrière des basketteurs professionnels. Ce projet illustre mes compétences en collecte de données, nettoyage, modélisation prédictive et communication des résultats.

## Objectif 🎯 :
L'objectif principal de ce projet était de développer un modèle prédictif capable de déterminer si un joueur de basket-ball aura une carrière professionnelle de plus de cinq ans. En utilisant des données historiques sur les performances des joueurs, des caractéristiques individuelles et des statistiques de match, j'ai entraîné plusieurs modèles et évalué leur performance pour prédire le succès futur des joueurs.

## Étapes du Projet ⛰️ :

### Collecte de Données :
- Collecte de données sur les carrières des joueurs via Kaggle
- Importation sur JupyterLab
￼
￼<img width="869" alt="Capture d’écran 2024-03-24 à 09 52 27" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/91086530-aa99-4400-99ec-68497db93c93">

<img width="877" alt="Capture d’écran 2024-03-24 à 09 49 39" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/2ec47fb6-3b26-49b5-a9f6-997ba241c7cb">

### Exploration des Données :
- Analyse exploratoire pour comprendre les tendances et les relations entre les variables.
- Visualisation des données pour identifier les caractéristiques importantes des joueurs à prendre en compte dans la modélisation.
python

<img width="388" alt="1340 non-null" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/e4746e7d-656d-486a-9a00-3a93943ea002">

### Traitement de la donnée:
- Séparation en base Train et base test
- Traitement et remplacement des valeurs nulls
- Standardisation de la données (features = variables numériques) 
- MinMaxScaler() & fit_transform()

<img width="874" alt="Capture d’écran 2024-03-24 à 09 58 11" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/09d568d6-532d-4f76-8267-7eb100b7c11a">
<img width="881" alt="Capture d’écran 2024-03-24 à 09 59 15" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/99dc84cf-a328-4ee1-9230-ba867298afdd">
<img width="967" alt="Capture d’écran 2024-03-24 à 10 03 22" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/4f63882b-f34c-4dbc-90ab-1f74d8ee5824">
<img width="980" alt="Capture d’écran 2024-03-24 à 10 04 42" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/3c9aa256-19df-4324-a2fc-77cfe5c19331">
<img width="969" alt="Capture d’écran 2024-03-24 à 10 10 38" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/2bdcc135-0870-444c-993c-f1feeed4c785">
<img width="964" alt="Capture d’écran 2024-03-24 à 10 12 48" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/b2f26899-fdc1-473e-a5ad-e30bf9c9b56a">

### Modélisation Prédictive :
- Mise en place d’une fonction pour mesurer la performance des différents modèles
- Entraînement de plusieurs modèles de machine learning, y compris Modèle de Régression Logistique, Random Forest et LightGBM, Arbre de décision, SVM pour prédire la durée de carrière des joueurs.
- Évaluation des modèles en utilisant des métriques telles que l'AUC, le taux de succès et le taux d'erreur.
python￼

<img width="960" alt="Capture d’écran 2024-03-24 à 10 30 59" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/31e8e9b1-453c-4876-84e2-79c9964d8419">
<img width="819" alt="Capture d’écran 2024-03-24 à 10 34 53" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/8a363c8a-9f81-4451-bbc4-1bfa807c245a">
<img width="905" alt="Capture d’écran 2024-03-24 à 10 37 51" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/fe5d8f2b-7c52-4469-8af0-2ed1f3d1e7d0">
<img width="821" alt="Capture d’écran 2024-03-24 à 10 39 05" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/439a3faa-b3d2-400b-8956-ee4809cf948f">
<img width="999" alt="Capture d’écran 2024-03-24 à 10 40 24" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/2e7a7efa-32dd-4887-8f63-310bb1354ca3">
<img width="725" alt="Capture d’écran 2024-03-24 à 10 41 28" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/745ae342-df1a-4ee6-8dd5-0e8aed9c7ec8">
<img width="537" alt="Capture d’écran 2024-03-24 à 11 13 56" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/4f18bc71-1110-47a9-a282-10de522ff01d">
<img width="634" alt="Capture d’écran 2024-03-24 à 11 14 39" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/90ffde8b-1b63-4cd6-b1f3-36d8cb97dfa5">
<img width="841" alt="Capture d’écran 2024-03-24 à 11 19 46" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/8f6ae26e-2495-4ec7-bf41-4f92654b8dc3">
<img width="847" alt="Capture d’écran 2024-03-24 à 10 48 52" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/3392d452-ec54-4ab1-a856-9470a1fdd5c8">
<img width="743" alt="Capture d’écran 2024-03-24 à 10 50 36" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/81cd5697-3f40-4b62-9566-5afb07928808">
<img width="762" alt="Capture d’écran 2024-03-24 à 10 51 34" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/5d35d665-0d52-4772-a938-7ac7a00e4471">

### Analyse des Résultats :
- Comparaison des performances des différents modèles pour sélectionner le meilleur modèle.

<img width="808" alt="Capture d’écran 2024-03-24 à 10 51 58" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/ff0654b1-c57d-4313-8bea-a8f39921437f">
<img width="870" alt="Capture d’écran 2024-03-24 à 10 55 52" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/c9a83a15-006e-45c8-b2a0-43da62b8cbd9">
<img width="772" alt="Capture d’écran 2024-03-24 à 10 57 33" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/236c1e62-cd4e-4492-9cb0-d3df8096fe1a">
<img width="1169" alt="Capture d’écran 2024-03-24 à 11 00 31" src="https://github.com/RobertoMaillot/Roberto-s-portfolio/assets/107147475/20da98d9-93d0-4cbb-bc12-b872625a1f6a">

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
