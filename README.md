# HOUSE PRICES
[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-360/)
![Docker](https://img.shields.io/badge/docker-no-yellowgreen.svg)

Dans le cadre de la formation Data / IA à l'Ecole IA Microsoft (Powered by Simplon), il a été demandé de travailler sur un projet d'analyse prédictive.
D'abord effectué directement sur la plateforme en ligne [BigML](https://bigml.com/), l'ensemble de processus d'apprentissage automatique supervisé a du être réalisé sur Python grâce à Jupyter Notebook.

**But :** pouvoir établir une prédiction et transmettre le résultat sur [Kaggle](https://www.kaggle.com/), une plateforme web organisant des compétitions en science des données.

Pour retrouver la compétition en question, vous retrouverez tous les renseignements et datasets ainsi que le classement directement sur cette page : [HousePrices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview).

## Mise en place de l'environnement de travail

**Etape 1 : Inscriptions**

* Créez un compte sur Kaggle ;
* Puis un compte sur GitHub si vous souhaitez mettre votre projet en ligne et de façon publique ;

**Etape 2 : Environnement de travail**

Tournant sans Docker, les scripts suivants fonctionnent avec [Anaconda](https://www.anaconda.com/distribution/#download-section). Installez la version compatible avec votre système d'exploitation.

Une fois installé, ouvrez Anaconda et créez votre environnement de travail (différent du "base (root)"). Pour cela :
- allez sur "Environments": 

![](https://zupimages.net/up/20/02/7qjy.png)

- Et sur "Create" (bas de la fenêtre):

![](https://zupimages.net/up/20/02/g0s7.png)

- Une fenêtre s'ouvre. Entrez un nom, cochez "R" et "Python" et choisissez la version Python "3.7":

![](https://zupimages.net/up/20/02/y3u8.png)

Si vous ne la trouvez pas dans le menu déroulant, pas de panique et allez dans la barre des tâches au dessus. Cliquez sur "Update index" :

![](https://zupimages.net/up/20/02/bqha.png)

**Etape 3 : Installation des modules**

Pour cela, dans votre environnement, sélectionnez "All" et tapez dans la barre de recherche :

* "pandas"

![](https://zupimages.net/up/20/02/wxa7.png)

Sélectionnez la version 0.25.1

* "numpy". Sélectionnez la version 1.16.5
* "matplotlib". Sélectionnez la version 3.1.1
* "keras". Sélectionnez la version 2.2.4
* "seaborn". Sélectionnez la version 0.9.0
* "scipy". Sélectionnez la version 1.3.1
* "tensorflow". Sélectionnez la version 1.15.0
* "scikit-learn". Sélectionnez la version 0.21.3

**Etape 4 : Installation de Jupyter Notebooks**

Cliquez sur Home dans la barre de gauche. Puis, sous Jupyter Notebooks, cliquez sur "Install" :

![](https://zupimages.net/up/20/02/eqyb.png)

Patientez et voilà, votre environnement est prêt !

**Etape 5 : Préparation au lancement des scripts**

- Téléchargez les scripts Jupyter Notebooks : [ici](https://github.com/Simplon-IA-Bdx-1/house-prices-ns-rx)

- Placez les à l'endroit de votre choix.

- Téléchargez les datasets nécessaires (train.csv et test.csv) : [ici](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

- Placez ces 2 fichiers dans le même dossier que les scripts Jupyter Notebooks.

- Dans Anaconda, lancez l'application Jupyter dans "Home" :

![](https://zupimages.net/up/20/02/f1bm.png)

Un onglet de votre navigateur web va s'ouvrir automatiquement et vous amènera dans votre dossier utilisateur sur votre machine. Naviguez jusque dans votre dossier où se trouvent tous les fichiers précédemment placés. 

Cliquez sur celui que vous souhaitez exécuter et pour lancer chaque cellule, pressez les touches SHIFT + ENTREE (en même temps). Ou si vous souhaitez toutes les lancer d'un coup, allez dans l'onglet "Cell" puis "Run Cells".

## Composition du projet

* Un script contenant une [analyse exploratoire de données (EDA)](https://github.com/Simplon-IA-Bdx-1/house-prices-ns-rx/blob/master/HousePrices_analysis.ipynb) ;
* Un script content [une prédiction avec Keras / Tensorflow](https://github.com/Simplon-IA-Bdx-1/house-prices-ns-rx/blob/master/HousePrices_keras.ipynb)
* Un script content [une prédiction avec XGBoost sur les 'meilleurs features'](https://github.com/Simplon-IA-Bdx-1/house-prices-ns-rx/blob/master/D_most_relevant_features_xgb_gscv.ipynb)

## Auteurs

* **Rachel X.** - [Profil GitHub](https://github.com/rachelrwf)
* **Nicolas SEVERINO** - [Profil GitHub](https://github.com/nicolasseverino/)
