# Projet ExacDatamente

Construire un Dashboard à partir de Datasets non structurés et fournis sous format CSV.

## Mission

Analyse des datasets fournis au format CSV pour réalisation d'une nouvelle base de données.
modélisation du schéma réalisé en UML. Mise en oeuvre de création de la BDD sur PostGreSQL avec
des scripts Python et SQL. Requêtes SQL sur la BDD puis création de visualisation avec MatPlotLib 
pour le dashboard final, réalisé en HTML avec la bibliothèque Jinja2.
    
### Pré-requis

Pour la réalisation du projet, utilisation des programmes suivants :

   - Python 3.8.6 (+ requirements.txt)
        
   - Logiciels : 
       - PostGreSQL 4.5
       - DB Browser 3.12
       - DBeaver 7.3.5
       - Star UML 3.0.1
       - Figma 93.4

### Project Organization
------------

    ├── README.md                                         <- Le README du siècle.
    │
    ├── CSV_Tables
    │   ├── logistics.csv                                 <- Document CSV créé pour l'importation des données
    │   ├── manufacturer.csv                              <- Document CSV créé pour l'importation des données
    │   ├── prices.csv                                    <- Document CSV créé pour l'importation des données
    │   ├── product.csv                                   <- Document CSV créé pour l'importation des données
    │   └── reviews.csv                                   <- Document CSV créé pour l'importation des données
    │
    ├── Data
    │   ├── DatafinitiElectronicsProductData              <- Fichier d'origine fournit par le client
    │   └── DatafinitiElectronicsProductsPricingData      <- Fichier d'origine fournit par le client
    │
    ├── Docs
    │   └── Projet EXACDATAMENTE.pdf                      <- Planning prévisionnel du projet
    │
    ├── Jinja2
    │   ├── html
    │   │   ├── img                                       <- Dossier contenant les images présentes dans le dashboard
    │   │   └── index.html                                <- Dashboard final au format HTML
    │   │
    │   └── template
    │       └── base.html                                 <- Template servant à la création du dashboard
    │
    ├── Schema
    │   ├── Etape Projet.mdj                              <- Schéma UML de la réalisation du projet
    │   ├── Maquette.fig                                  <- Maquette du dashboard
    │   ├── NewBDD.mdj                                    <- Schéma UML de la BDD créée pour le projet
    │   └── SchemaCSV.mdj                                 <- Schéma UML original des documents CSV fournis 
    │
    ├── Snaps                                             <- Dossiers contenant toutes les images présentes dans les notebooks
    │
    ├── 01_Analyzing_CSV.ipynb                            <- Première partie du projet : l'analyse des CSV et des données
    │
    ├── 02_Create_Query_Viz_Schema                        <- Seconde partie : création du schéma de la BDD et des futures requêtes
    │
    ├── 03_Create_CSV_tables.ipynb                        <- Troisème partie : création des CSV servant à l'importation des données
    │
    ├── 04_Create_DB.ipynb                                <- Quatrième partie : création de la BDD et importation des données
    │
    ├── 05_Query_and_Viz.ipynb                            <- Cinquième partie : réalisation des requêtes et des graphiques
    │
    ├── 06_App_Viz.ipynb                                  <- Sixième partie : création du dashboard
    │
    ├── requirements.txt                                  <- Fichier servant à la création de l'environnement virtuel
    │
    └── Tuto_Recherche.ipynb                              <- Tutoriel de recherche d'une solution à un prblème technique


--------


## Auteur

* **Corentin Pingeon** _alias_ [@CPingeon](https://github.com/CPingeon)

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)