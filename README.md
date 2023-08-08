# OCR4
## OpenClassRooms project 4: Segmentez des clients d'un site e-commerce
Pour cette mission, Olist vous fournit une [base de données](https://www.kaggle.com/olistbr/brazilian-ecommerce) anonymisée comportant des informations sur l’historique de commandes, les produits achetés, les commentaires de satisfaction, et la localisation des clients depuis janvier 2017.

### Mission 
  1. Aider les équipes d’Olist à comprendre les différents types d'utilisateurs.
  2. Méthodes non supervisées pour regrouper des clients de profils similaires:
      - **RFM**
    ![image](https://github.com/SebastianSosa/OCR4/assets/22368172/e366e903-a753-4e64-b19f-709e84e404f6)

      - **Kmean, analyse de silhouette, TSNE,  stabilité des clusters dans le temps, évolution de l’ARI**
        ![image](https://github.com/SebastianSosa/OCR4/assets/22368172/b0804247-e9ed-4884-86d8-739654e92f95)
        
      -  **DBSCAN, calcul de la proximité des données entre elles en utilisant Nearest Neighbours, Optimisation d'epsilone par evaluation des différentes valeurs**
        ![image](https://github.com/SebastianSosa/OCR4/assets/22368172/1f3ee638-e452-4146-824f-be2f7668edac)

      - **TSNE**
        
        ![image](https://github.com/SebastianSosa/OCR4/assets/22368172/c82b5075-be16-44e6-b4eb-567e26b38213)






### Compétences évaluées
  1. Adapter les hyperparamètres d'un algorithme non supervisé afin de l'améliorer
  2. Évaluer les performances d’un modèle d'apprentissage non supervisé
  3. Transformer les variables pertinentes d'un modèle d'apprentissage non supervisé
  4. Mettre en place le modèle d'apprentissage non supervisé adapté au problème métier

### Livrables 
  1.  Un notebook de l'analyse exploratoire (non cleané, pour comprendre votre démarche).
  2.  Un notebook (ou code commenté au choix) d’essais des différentes approches de modélisation (non cleané, pour comprendre votre démarche).
  3.  Un notebook de simulation pour déterminer la fréquence nécessaire de mise à jour du modèle de segmentation.
  4.  Un support de présentation pour présenter votre travail à un collègue.
