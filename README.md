# Modélisation Prédictive de l'Impact des Catastrophes Naturelles pour Guider les Stratégies d'Assurance

Ce projet vise à analyser et prédire l'impact humain des catastrophes naturelles à l'échelle mondiale, dans le but de fournir des insights clés au secteur de l'assurance pour guider leurs stratégies de gestion des risques.

## Contexte et Objectifs

Les catastrophes naturelles représentent un défi majeur pour le secteur de l'assurance. Une compréhension fine de leur impact potentiel est essentielle pour développer des stratégies de tarification, de prévention et de réassurance adaptées.

Ce projet a pour objectifs principaux :
1. D'analyser les patterns d'impact des catastrophes naturelles en termes de décès et de population affectée
2. De développer des modèles prédictifs pour estimer la sévérité des futurs événements
3. De construire des indicateurs de risque synthétiques pour aider à la prise de décision assurantielle

## Données

L'analyse s'appuie sur les données de la base EM-DAT (Emergency Events Database) qui recense les catastrophes naturelles survenues dans le monde entre 1980 et 2024. Le jeu de données nettoyé utilisé pour l'analyse est disponible dans le fichier `data_cleaned_final.csv`.

## Méthodologie

Le projet suit une approche de science des données complète, allant de l'exploration des données à la modélisation prédictive et à la construction d'indicateurs décisionnels :

1. Nettoyage et préparation des données
2. Analyse descriptive univariée et bivariée pour comprendre les patterns d'impact
3. Développement de modèles prédictifs par machine learning (Random Forest, XGBoost, ...)
4. Élaboration d'indicateurs de risque composites, dont le Score Global de Risque Assurantiel (SGRA)

L'ensemble des analyses et du code sont détaillés dans le notebook R Markdown `Projet_ML.Rmd`.

## Principaux Résultats

- Le nombre de personnes affectées est identifié comme le principal prédicteur du nombre de décès
- Des disparités régionales significatives sont mises en évidence dans les profils de risque catastrophique
- Le Score Global de Risque Assurantiel (SGRA) permet de prioriser les actions assurantielles par région

Une discussion approfondie des résultats et de leurs implications pour le secteur de l'assurance est proposée dans le notebook.

## Navigation

- `Projet_ML.Rmd` : Notebook R Markdown contenant l'ensemble des analyses et du code
- `Projet_ML.html` : Version HTML du notebook, avec les résultats et visualisations
- `data_cleaned_final.csv` : Jeu de données nettoyé utilisé pour les analyses

N'hésitez pas à explorer le notebook `Projet_ML.html` pour une présentation détaillée de la démarche et des résultats du projet.
