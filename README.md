# Mall-Customer-Segmentation

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1I03_OYmqh0LhHW5mWzMkfjVAbged1cIk?usp=sharing)

---

## Contexte
Ce projet vise à étudier les principes de comportement et de la segmentation client en utilisant des algorithmes de clustering.

## Données
Les données utilisées dans ce projet sont:
- Source: [Kaggle dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data?select=Mall_Customers.csv)
- Format: fichier csv avec 5 columns ID/Age/Genre/Revenu Annuel/Score de Dépense

## Méthode
L'approche comporte les étapes suivantes:
1. Data preprocessing
   - Nettoyage: gérer les potentielles valeurs manquantes, doublons et incohérences dans les formats et valeurs des caractéritiques  
   - Transformation: using a sentence transformers model to get embeddings for each sentence and a label encoder for the classes
   - Validation
2. Analyse
   - EDA pour mieux comprendre les données utilisées
   - Visualiasation des caractéristiques
3. Implémentation
   - Algorithme K-means
   - Algorithme Gaussian Mixture Model (GMM)
4. Evaluation
   - Inertie & Silhouette score pour le modèle K-means
   - AIC/BIC & Silhouette score pour le modèle GMM
   - Analyse/Visualisation des cluster et interprétation potentielle des résultats

Limitations: faible quantité d'information pour effectuer des analyses plus complexes de segmentation
