# clustering_reductionDimension
# Segmentation Client par Clustering

## Contexte
Ce projet applique des techniques de clustering pour segmenter 
des clients selon leurs comportements d'achat, dans une optique 
marketing.

## Objectifs
- Appliquer KMeans, CAH et DBSCAN pour identifier des segments clients
- Réduire la dimensionnalité avec PCA et t-SNE pour visualiser les résultats
- Interpréter les segments d'un point de vue business

## Dataset
Source : [Kaggle - Customer Segmentation](https://www.kaggle.com/datasets/kaushiksuresh147/customer-segmentation)

## Méthodologie
1. Exploration et nettoyage des données (EDA, valeurs manquantes, outliers)
2. Encodage des variables catégorielles
3. Standardisation
4. Réduction de dimension (PCA)
5. Clustering (KMeans, CAH, DBSCAN)
6. Visualisation (t-SNE)
7. Interprétation métier des segments

## Résultats
- KMeans (K=4) : Score Silhouette = 0.1566
- CAH (K=4) : Score Silhouette = 0.1046
- DBSCAN : Score Silhouette = 0.40

[Insérer ici une image de la visualisation finale t-SNE]

## Segments identifiés
- **Segment 0** : [description du profil]
- **Segment 1** : [description du profil]
- **Segment 2** : [description du profil]
- **Segment 3** : [description du profil]

## Technologies utilisées
- Python (pandas, numpy, matplotlib, seaborn)
- Scikit-learn (KMeans, PCA, t-SNE, DBSCAN)
- Scipy (CAH)

## Installation
\`\`\`bash
pip install -r requirements.txt
\`\`\`

## Structure du projet
\`\`\`
├── notebook_clustering.ipynb
├── data/
├── requirements.txt
└── README.md
\`\`\`

## Auteur
[Ton nom] - [ton lien LinkedIn ou portfolio]
