# 🧪 Application Shiny – Uniformisation des unités de produits (g → kg)

## 📌 Contexte

Cette application Shiny a été développée dans le cadre d’un stage à **l’Institut Agro**, réalisé du **2 mai au 30 juin 2025**. Elle s’inscrit dans une démarche d’amélioration de la qualité des données issues de structures de circuits courts :

- **Cagette**
- **La Ruche qui dit Oui**
- **Socleo**
- **CoopCircuits**

Les bases de données traitées présentent des incohérences dans les unités de mesure des produits, en particulier l'utilisation non homogène des unités de poids. Le travail s’est donc concentré sur la **normalisation des unités de mesure**, en convertissant les valeurs exprimées en **grammes (g, gr, gramme, etc.)** vers des **kilogrammes (kg)**.

## 🎯 Objectif de l’application

Cette application permet :

- 📥 De charger une base de données produits ;
- 🔍 D’identifier automatiquement les quantités exprimées en grammes ;
- 🔁 De convertir ces quantités en kilogrammes ;
- 👁️‍🗨️ De visualiser les données transformées pour validation ;
- 📤 D’exporter les données nettoyées.

> ⚠️ **Important** : Les données utilisées étant confidentielles, **aucune base réelle n’est fournie** dans ce dépôt.

## 🛠️ Technologies utilisées

- [R](https://www.r-project.org/)
- [Shiny](https://shiny.posit.co/)
- [tidyverse](https://www.tidyverse.org/) :
  - `dplyr` pour la manipulation des données
  - `stringr` pour le traitement de texte
  - etc.

## ▶️ Lancer l'application

Depuis R ou RStudio :

```r
shiny::runApp("chemin/vers/le/dossier")
```

> Remplace `"chemin/vers/le/dossier"` par le chemin réel vers le répertoire de l'application.

## 📁 Structure du dépôt

```bash
.
├── config/            # Fichiers de configuration (si applicable)
├── www/               # Fichiers statiques (CSS, images, etc.)
├── global.R           # Chargement des librairies et données communes
├── server.R           # Logique serveur de l'application
├── ui.R               # Interface utilisateur
├── Real App.Rproj     # Fichier de projet RStudio
└── README.md          # Ce fichier
```

## 🧩 Cas d’usage généraux

Bien que conçue pour un besoin spécifique, l’application peut être réutilisée dans d'autres contextes :

- 🔄 Transformation d’unités dans toute base produit ;
- 🧼 Prétraitement de données pour l’analyse ou la visualisation ;
- ✅ Amélioration de la qualité des données dans des systèmes hétérogènes.
