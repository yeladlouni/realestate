Le but du lab est de prédire la valeur des biens immobiliers à partir des différentes variables contenues dans le dataset:
* households
* total_rooms
* total_bedrooms
...
  
1. Charger le dataset comme dataframe sur Spark
2. Spliter les données selon 3 splits:
    * train
    * validation
    * test
3. Créer un RForumla avec les variables à utiliser pour la prédiction
   Appliquer le RFormula sur les différents split pour générer les colonnes features et label
4. Créer un model linear regression pour
    * Entraîner le modèle avec les données train
    * Evaluer  le modèle en utilisant le split validation
    * Prédire les valeurs pour les données test
    
Bonus: Appliqer d'autre modèles (RandomForest, DecisionTrees....) pour prédire les prix 
