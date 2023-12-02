Projet de Classification Automatique d'Articles sur une Place de Marché

Introduction
Sur notre place de marché, les vendeurs postent des articles avec des photos et des descriptions, mais l'attribution manuelle des catégories est peu fiable. Pour améliorer l'expérience utilisateur, nous avons entrepris d'automatiser cette tâche en étudiant la faisabilité d'un moteur de classification des articles.

Mission
La Lead Data Scientist, Linda, a chargé d'étudier la faisabilité d'un moteur de classification. Dans la première itération, nous avons effectué une analyse visuelle des descriptions textuelles et des images, démontrant la possibilité de regrouper automatiquement des produits de même catégorie.

Étapes de l'Analyse
Prétraitement des données textuelles et d'image : Utilisation de différentes approches telles que bag-of-words, TF-IDF, Word2Vec, Glove, FastText, BERT et USE pour les données textuelles, et SIFT/ORB/SURF et CNN Transfer Learning pour les images.

Réduction en 2 dimensions : Projection des produits sur un graphique 2D, coloré selon la catégorie réelle.

Analyse visuelle : Étude du graphique pour évaluer la possibilité de regrouper automatiquement des produits de même catégorie.

Mesure de similarité : Calcul de la similarité entre les catégories réelles et les catégories issues d'une segmentation en clusters.

Résultats
La faisabilité de regrouper automatiquement des produits de même catégorie a été démontrée avec succès.

Deuxième Itération
Suite aux résultats positifs, Linda propose une deuxième itération pour réaliser une classification supervisée à partir des images, avec mise en place de la data augmentation pour optimiser le modèle.

Livrables
Notebooks : Contenant les fonctions pour le prétraitement, la feature extraction, l'étude de faisabilité, et la classification supervisée.
Script Python : Pour tester l'API de collecte de produits à base de "champagne" et extraire les données dans un fichier CSV.
Présentation de Soutenance : PowerPoint ou équivalent avec 30 slides maximum détaillant l'étude de faisabilité, la classification supervisée, et le test de l'API.


Prétraitement des Données Textes
Prétraitement des données textuelles, y compris la suppression de la ponctuation, la mise en minuscules, la tokenisation, le stemming, la lemmatisation, et la construction de features de type bag-of-words avec seuil de fréquence des mots et normalisation. Illustration avec un exemple.
Mise en œuvre de démarches de word/sentence embedding avec Word2Vec, BERT, et USE.
Garantie que le texte traité ne viole aucune propriété intellectuelle.
Prétraitement des Données Images
Utilisation de librairies pour le traitement du contraste, et présentation d'opérations de retraitement d'images.
Élaboration de fonctions pour extraire des features de type "bag-of-images" avec des algorithmes ORB, SIFT, SURF, et un algorithme de Transfer Learning basé sur CNN.
Assure que les images utilisées ne sont pas soumises à des droits de propriété intellectuelle.
Réduction de Dimension et Représentation Graphique
Justification de la nécessité de la réduction de dimension, application d'une méthode adaptée (ex. ACP), justification des choix de paramètres.
Utilisation d'au moins une technique de réduction de dimension, création d'au moins un graphique 2D, et analyse du graphique.
Collecte de Données via API
Définition de la stratégie de collecte, écriture et test de requêtes API, récupération des champs nécessaires, filtrage sur des critères spécifiques, stockage des données dans un fichier utilisable (CSV ou pickle), respect des normes RGPD.
Élaboration d'un Modèle d'Apprentissage Profond
Définition de la stratégie d'élaboration du modèle, séparation des jeux de données, absence de fuite d'information, test de plusieurs modèles (y compris Transfer Learning), optimisation des hyperparamètres.
Évaluation de la Performance des Modèles
Choix d'une métrique adaptée, explication du choix de la métrique, évaluation de la performance d'un modèle de référence, calcul d'au moins un autre indicateur, optimisation d'au moins un hyperparamètre, présentation d'une synthèse comparative des modèles.
Utilisation de Techniques d'Augmentation des Données
Utilisation de plusieurs techniques d'augmentation des données, présentation d'une synthèse comparative des améliorations de performance.
Compétences Évaluées
Utilisation de techniques d’augmentation des données
Prétraitement des données texte pour obtenir un jeu exploitable
Représentation graphique des données à grandes dimensions
Prétraitement des données image pour obtenir un jeu exploitable
Mise en œuvre de techniques de réduction de dimension
Définition de la stratégie de collecte de données en recensant les API disponibles
Définition de la stratégie d’élaboration d’un modèle d'apprentissage profond
Évaluation de la performance des modèles d’apprentissage profond selon différents critères
