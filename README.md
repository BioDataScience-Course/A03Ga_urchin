# Biométrie de *Parocentrotus lividus* Lamarck (1816)

## Objectifs

Ce projet est un travail en **binôme** à réaliser **sur plusieurs modules**. Le template correspondant est accessible à <https://github.com/BioDataScience-Course/A03Ga_urchin>. Vous allez devoir compléter les fichiers qui se trouvent dans le sous-dossier `docs` :

-   un carnet de notes **urchin_notebook.Rmd**, qui servira à explorer les données sur la biométrie des oursins
-   un rapport **urchin_report.Rmd**, qui présentera les éléments les plus pertinents de vos analyses

Vous devrez réaliser des graphiques, des tableaux et des analyses au cours des différents modules vus dans le cadre du cours de science des données I.

## Mise en situation

Les données employées dans le cadre de cette étude proviennent d'une recherche portant sur la croissance de l'oursin violet *Paracentrotus lividus* Lamarck (1816). Vous récupérez les données comme suit :

    SciViews::R
    urchin <- read("urchin_bio", package = "data.io")

N'hésitez pas à faire appel à la page d'aide de ce jeu de données

    .?urchin

## Progression

### Module 3 & 4

A la fin de ces modules, vous devez avoir décidé d'un but pour votre recherche. Il s'agit donc de se poser une question sur les données mises à votre disposition. Ajoutez au moins quatre graphiques pertinents en lien avec la question que vous vous posez dans votre rapport. Chaque graphique doit évidemment être commenté.

------------------------------------------------------------------------

### Module 5 & 6

A la fin de ces modules, vous devez avoir intégré au moins deux tableaux qui résument vos données. Ces tableaux doivent être pertinents et en lien avec la question élaborée lors des modules précédents.

Vous aurez aussi commencé à rédiger le rapport qui doit contenir les sections suivantes :

-   **Introduction** sur les organismes que vous étudiez
-   **But** qui présente en une ou deux phrases la question que vous vous posez sur ces données
-   **Matériel et méthodes**, une section qui explicite comment les données ont été acquises, ainsi que les outils informatiques que vous utilisez. Soyez précis (nom complet + version + citation ou lien)
-   **Résultats** avec vos différents tableaux et graphiques et leur interprétation
-   **Discussion** (vide car sera remplie au Q2)
-   **Conclusion** (vide car sera remplie au Q2)
