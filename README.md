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
