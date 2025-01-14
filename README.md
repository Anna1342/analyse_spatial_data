# Projet exploration des fonctionnalités de GeoPandas

## Description
Ce projet vise à explorer et manipuler des données géospatiales en utilisant la bibliothèque Python GeoPandas. À travers des opérations comme le filtrage, l'agrégation, les transformations géométriques, et les projections, nous analysons des jeux de données sur les communes françaises, les villes américaines et européennes. Ce projet inclut également des visualisations cartographiques et des calculs de distances géographiques.

## Prérequis
- Python 3.6 ou supérieur
- Bibliothèques Python nécessaires :geopandas, matplotlib, pandas, shapely, numpy, mapclassify
- Fichiers requis : Communes françaises.zip, citiesfr.csv, ne_110m_admin_0_countries.zip, us_nation.zip, uscities.csv).

## Installation
1. Clonez le dépot ou téléchargez les fichiers nécéssaires
2. Installez les bibliothèques requises avec la commande suivante en bash :
pip install geopandas matplotlib pandas shapely numpy mapclassify
3. Exécutez chaque étape du script dans un environnement Python (par exemple, Jupyter Notebook) pour visualiser les résultats et comprendre les concepts.
  
## Utilisation
1. Manipulations géométriques de base
2. Création de cartes thématiques colorées par commune (NOM).
3. Filtrage et affichage des communes spécifiques, comme "CC Haut-Jura Saint-Claude".
4. Fusion des données géographiques et non géographiques(transformation des villes françaises en GeoDataFrame en utilisant leurs coordonnées).
5. Délimitation d'une région.
6. Calcul de distances entre géométries
7. Cartes thématiques avec classification
8. Vérification des frontières entre pays
9. Affichage des deux pays sur une carte.

## Résultats attendus
- Cartes visualisant les communes, les villes, et leurs interactions.
- Confirmation des intersections géométriques entre pays.
- Distances entre villes ou régions, calculées avec précision.
- Création de cartes thématiques basées sur des classifications.
  
## Auteurs
- Anna Szwarcbart

## Licence
Ce projet est sous licence [MIT].
