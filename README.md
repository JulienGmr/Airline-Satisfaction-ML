# Analyse Satisfaction Aérienne (Machine Learning)

**Projet Étudiant - Master IREN (Université Paris-Dauphine)**

Ce projet utilise l'Intelligence Artificielle pour analyser des milliers d'avis de passagers aériens.
L'objectif est de comprendre ce qui crée la satisfaction et de prédire si un client recommandera la compagnie.

##  Données (Source Externe)

Les données utilisées proviennent du **Skytrax User Reviews Dataset**.
 Le fichier de données n'est pas inclus directement dans ce dépôt.

 **Lien pour télécharger les données :** [https://github.com/quankiquanki/skytrax-reviews-dataset](https://github.com/quankiquanki/skytrax-reviews-dataset)

**Instructions d'installation :**
1. Cliquez sur le lien ci-dessus.
2. Téléchargez le fichier `airline.csv`.
3. Placez ce fichier dans le dossier `notebook/` à la racine de ce projet.

##  Ce que fait le code

J'ai construit une analyse en 4 étapes :

1.  **Nettoyage :** Tri et correction des commentaires bruts pour les rendre utilisables.
2.  **Segmentation (Clustering) :** Regroupement automatique des passagers par profil (ex: "Les sensibles au prix").
3.  **Analyse de Texte (NLP) :** L'ordinateur lit les avis pour comprendre les sujets (Retards, Repas, Personnel...).
4.  **Prédiction & Carte :**


##  Résultats Clés

* **Le Prix avant tout :** Le rapport "Qualité/Prix" est le critère le plus important pour les passagers, loin devant le confort du siège.
* **Fracture Géographique :** Les vols vers l'Asie sont excellents, tandis que les vols vers l'Amérique du Nord concentrent les plaintes.




