# Application Shiny – Uniformisation des unités de produits (g → kg)

## Contexte

Cette application Shiny a été développée dans le cadre d’un stage réalisé à **l’Institut Agro** du **2 mai au 30 juin 2025**. Le travail s’inscrit dans une démarche d’amélioration de la qualité des données issues de plusieurs structures de circuits courts : **Cagette**, **La Ruche qui dit Oui**, **Socleo**, et **CoopCircuits**.

Ces bases de données contiennent des informations produits hétérogènes, notamment en ce qui concerne les unités de mesure. L’un des objectifs principaux de ce stage était de **nettoyer et harmoniser les quantités** renseignées, particulièrement en transformant toutes les quantités exprimées en **grammes (g, gramme, gr, etc.)** en **kilogrammes (kg)**.

## Objectif de l'application

L'application Shiny permet de :

- Charger des bases de données produits ;
- Identifier et convertir automatiquement les quantités exprimées en grammes vers des kilogrammes ;
- Visualiser les transformations effectuées pour vérification ;
- Exporter les données nettoyées.

**⚠️ Remarque : Les données traitées étant confidentielles, aucun jeu de données réel n'est fourni dans ce dépôt.**

## Utilisation possible

Bien que développée initialement pour le nettoyage d'unités dans le cadre du stage, l'application est suffisamment générique pour être utilisée dans d'autres contextes impliquant :

- La transformation d'unités dans des bases de données produits ;
- Le prétraitement de données pour analyse ou visualisation ;
- Des démarches d’amélioration de la qualité des données.

## Lancer l'application

```r
# Depuis R ou RStudio
shiny::runApp("chemin/vers/le/dossier")
```

Technologies

    R

    Shiny

    tidyverse (notamment dplyr, stringr, etc.)

Structure du dépôt

├── app.R                 # Code principal de l'application Shiny
├── README.md             # Ce fichier
└── data/                 # (vide ou exemples fictifs si besoin)

