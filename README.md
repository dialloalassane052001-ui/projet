# Projet Deep Learning - Big Data _M2



## Sujet

Vous allez, dans ce projet, entraîner plusieurs réseaux de neurones à classifier des paysages. Vous utiliserez pour cela le dataset Landscapes disponible [ici](https://github.com/ml5js/ml5-data-and-models/tree/master/datasets/images/landscapes).

Il s'agit d'un dataset comprenant 4000 images appartenant à 7 catégories.

![Exemples du dataset](./Image/landscape_example.jpg)*Exemples du dataset*

### Objectifs

Vous devez :

1.  **Séparer vos données** en 2 : un jeu d'apprentissage (80%) et un jeu de validation (20%).
2.  **Entraîner un réseau de convolutions** que vous aurez défini vous-même.
3.  Utiliser de manière individuelle différentes **techniques d'amélioration** de la généralisation (data augmentation, dropout, etc.) pour améliorer votre modèle.
4.  Utiliser un **réseau pré-entraîné** pour améliorer vos performances (transfer learning).
5.  **Comparer les résultats** produits par les étapes 2, 3 et 4 dans un tableau récapitulatif (en utilisant le jeu de validation).
6.  Afficher quelques **exemples d'erreurs** de votre meilleur réseau et ses prédictions pour ces images.
7.  **Visualiser les projections** dans l'espace des features à l'aide d'une t-SNE sur un sous-ensemble du dataset (quelques centaines d'images).
8.  À l'aide des features calculées par votre réseau, choisir une image au hasard dans le dataset et **afficher les 3 images les plus proches** au sens de la distance euclidienne. Vous pourrez, si vous le souhaitez, utiliser les plus proches voisins de Scikit-Learn (`sklearn.neighbors.NearestNeighbors`).

