# Projet_data_scientist
Ce projet consiste à faire une etude sur le score de donner un prêt à  un client en fonction de son historique de prêt ,son statut marital et son salaire



1.	collecte des données
Pour cela on va utiliser la base de données de Kaggle.

- importation des packages
Pandas:  car permet de manipuler les données sous forme de tableau: fusionner, importer etc...
Numpy:  car permet de faire des calcules mathematiques sur des tableaux  et des matrices
Matplotlib et Seaborn: pour la visualisation sous forme graphique
Pickle : pour generer le modèle car on va deploier notre modèle dans une application

2.	Nettoyage de la base de données (data cleaning)

On essaye de voir les données manquantes car ça peut faussé les resultats

En affichant la base de donnée df, on remarque que notre df à 614 lignes et 13 colonnes.Mais par defaut on voit que 10 lignes.
Pour afficher toutes les lignes, on fait appelle l'option display
Pour reduire la taille de df à  10 on fait appelle à set_option
Maintenant qu'on a notre base de données df, pour avoir des renseignement sur les valeurs manaquantes on peut faire appelle à : info

- Renseigner les valeurs manaquantes: pour cela on va créer deux listes:  une liste categiruques et une liste numerique
    - Pour les variables categoriques, on va remplacer les données manquantes par les valeurs qui se repète le plus
    - Pour les variables numeriques on va remplacer les données manquantes par les valeurs par la valeurs precedantes de la 
      même colonne
      
3.	Analyse exploratoire :
On utilise la visualisation on comprendre notre base de données
4.	Préparation du modèle du machine learning
5.	Déploiement du modèle
On va intégrer notre modèle dans une application ou une application Web en utilisant un micro-framework (FLASK) utilisable par une personne non technique pour avoir des infos 
