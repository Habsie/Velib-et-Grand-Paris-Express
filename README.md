# Velib-et-Grand-Paris-Express
Stratégie proactive de Vélib'Metropole pour accompagner le GPE



Purpose

[FR] Comment Vélib’Métropole peut-elle continuer à se positionner comme un acteur majeur dans le développement du Grand Paris Express.



Pre-requisites

- Jupyter Notebook ou Google Colab
- Tableau Software



Installation

- `pip install -r requirements.txt`



Folder Manifest
Data

Données à disposition : 

❖	Velib_Mars_2022.csv

❖	Velib_Avril_2022.csv

❖	Velib_Mai_2022.csv => fichier utilisé pour l’analyse

Données trouvées open sources : 

❖	grille_densite_7_niveaux_detaille_2022.xlsx

❖	base_cc_comparateur.xlsx

❖	emplacement-des-gares-idf.csv

❖	Zones-d-arrets.csv

❖	gares_gpe.csv

❖	GPE_GARE_LOCALISATION.csv

❖	repertoire_geeographique_des_communes_d_ile-de-france.csv

Données après traitement :

❖	Vélib_Mai2022_enrichie ==> fichier de données d’activité des stations vélib’ du mois de Mai après nettoyage et enrichissement

❖	Villes_idf_densite.csv  ==> fichier contenant les informations de la segmentation des villes en IDF en fonction de la densité de la population/km2

❖	stations-velib.csv  ==> fichier listant les stations vélib’ en IDF

❖	stations-idf.csv ==> fichier listant les stations du réseau ferré en IDF(métro et tram) et les stations vélib existantes dans un rayon de 300m

❖	stations-gpe.csv ==> fichier listant les stations du GPE et les stations vélib’ à 300m

❖	Sources.docx = => Liste des sources des fichiers utilisés

❖	Méta-Données pour les données à disposition


Notebook
❖	Vélib_Mai2022_enrichie.ipynb  ==> code pour nettoyer le fichier de Mai et son enrichissement

❖	Villes_idf.ipynb  ==> code pour lister les villes d’IDF et la segmentation en fonction de la sensité pop/km2

❖	stations_velib.ipynb ==> code pour lister les stations vélib’ en IDF

❖	stations-idf.ipynb  ==> code pour lister les stations du réseau ferré en IDF(métro et tram) et les stations vélib existantes dans un rayon de 300m

❖	stations-gpe.ipynb ==> code pour lister les stations du GPE et les stations vélib’ à 300m



Etape d'analyses:

Etape 1 : Préparation des datasets

Vélib’ Mai 2022
-	Notebook Con Vélib_Mai2022_enrichie

Etape 2 : Préparation du fichier des stations de vélib’ en IDF
-	Notebook stations_velib

Etape 3 :  Préparation fichier Densité population par villes
-	Notebook Villes_idf
Etape 4 : Préparation fichier Stations réseau ferré IDF et les stations vélib’ à 300m
-	Notebook stations_idf 

Etape 5 : Préparation fichier Stations GPE
-	Notebook stations_gpe
Etape 6 : Analyse business pour une stratégie d’implantation de Vélib’ autour du GPE 
Analyse faite à partir du logiciel Tableau
-	Analyse sous format ppt






