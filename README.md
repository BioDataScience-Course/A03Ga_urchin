# Biométrie de *Parocentrotus lividus* Lamarck (1816)

## Avant-propos

Cette séance d’exercices est en cours de développement. N’hésitez pas à vérifier le lien suivant afin de voir si des modifications n’ont pas été apportées dans les consignes : <https://github.com/BioDataScience-Course/...>

## Objectifs

Ce projet est un travail en **binôme** à réaliser **sur plusieurs modules**.

Vous allez devoir compléter les fichiers qui se trouvent dans le dossier `docs` : 

- un carnet de laboratoire, **urchin_notebook.Rmd**, qui servira à explorer les données sur la biométrie des oursins 
- un rapport scientifique, **urchin_report.Rmd**, qui présentera les éléments les plus pertinents de vos analyses 

Vous devrez réalisez des graphiques, des tableaux et des analyses au cours des différents modules vus dans le cadre du cours de science des données I. 

## Mise en situation

Les données employées dans le cadre de cette étude proviennent des recherches du professeur Philippe Grosjean portant sur la croissance de *Paracentrotus lividus* Lamarck (1816).

Vous pouvez importer les données via la fonctions suivantes :

```
urchin <- data.io::read("urchin_bio", package = "data.io")
```

N'hésitez pas à faire appel à la page d'aide de ce jeu de données

```
.?urchin_bio
```

## Etat de progression 

### Module 2, 3 & 4

A la fin de ces modules, vous devez avoir décidé d'un but dans votre recherche. Il s'agit donc de se poser une question sur les données mise à votre disposition. Ajoutez au moins 4 graphiques pertinents en lien avec la question que vous vous posez dans votre rapport. Chaque graphiques doit évidement être commenté dans le texte. 

-----

### Module 5 & 6

A la fin de ces modules, vous devez avoir intégré au moins 2 tableaux qui résument vos données. Ces tableaux doivent être pertinent et en lien avec votre question de recherche fixé lors des modules précédents.

Votre rapport écrit doit contenir les sections suivantes :

- une section **introduction** sur les organismes que vous étudiez
- une section **but** qui présente la question que vous vous posez sur ces données
- une section **m&m** courte qui présente l'acquisition des données et les outils informatiques que vous utilisez. Soyez précis pour ce dernier point. 
- une section **résultats** qui présente vos différents tableaux et graphiques. Attention ceux-ci doivent être annotés ! 
- une section **discussion** vide
- une section **conclusion** vide

-----

### Module 7 & 8

A la fin de ces modules, vous devez avoir ammélioré votre rapport en tenant compte des remarques de l'évaluation du Q1 (même si ce n'est pas ce rapport qui a été corrigé). 

Si la réalisation d'un test de chi^2^ se prête à la question de recherche que vous vous êtes posé, intégrez cette analyse statistique dans vos résultats

-----

### Module 9 à 12

A la fin de ces modules, vous devez avoir intégré à la section **résultats** 3 tests statistiques que vous jugez pertinent pour répondre à la question de recherche que vous vous êtes posée. N'oubliez pas de commenter et d'interpréter ces tests. 

Vous devez également avoir complété les sections **discussion** et **conclusion** de votre rapport. 
