✈️ Analyse Satisfaction Aérienne (Machine Learning)
Projet Étudiant - Master IREN (Université Paris-Dauphine)

Ce projet utilise l'Intelligence Artificielle pour analyser des milliers d'avis de passagers aériens. L'objectif est de comprendre ce qui crée la satisfaction et de prédire si un client recommandera la compagnie.

Données (Source Externe)
Les données utilisées proviennent du Skytrax User Reviews Dataset. Le fichier de données n'est pas inclus directement dans ce dépôt.

Lien pour télécharger les données : https://github.com/quankiquanki/skytrax-reviews-dataset

Instructions d'installation :

Cliquez sur le lien ci-dessus.
Téléchargez le fichier airline.csv.
Placez ce fichier dans le dossier data/ à la racine de ce projet.
Ce que fait le code
J'ai construit une analyse en 4 étapes :

Nettoyage : Tri et correction des commentaires bruts pour les rendre utilisables.
Segmentation (Clustering) : Regroupement automatique des passagers par profil (ex: "Les sensibles au prix").
Analyse de Texte (NLP) : L'ordinateur lit les avis pour comprendre les sujets (Retards, Repas, Personnel...).
Prédiction & Carte :
Un modèle capable de deviner la recommandation avec 89.6% de précision.
Une carte interactive des lignes aériennes (Vert = Bien, Rouge = Problème).
