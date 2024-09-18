# Documentation du Projet Chatbot

Bienvenue dans le projet de chatbot ! Ce document fournit des instructions pour cloner le dépôt, configurer l'environnement et exécuter le modèle.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les outils suivants :

- [Python](https://www.python.org/downloads/) (version 3.8 ou ultérieure)
- [Git](https://git-scm.com/downloads)
- [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) (pour la gestion des environnements)

## Cloner le Dépôt

Pour cloner ce dépôt, utilisez la commande suivante :

```bash
git@github.com:GiovanniTY/workshop.git
 ```

## Configurer l'Environnement

Vous avez deux options pour configurer l'environnement :

## Option 1 : Utiliser Conda

1. Accédez au répertoire du projet :

```bash
cd my_rasa_project
 ```
2. Créer un environnement virtuel avec Conda :

``` bash
conda create --name chatbot_env python=3.8
```

3. Activer l'environnement :
```bash
conda activate chatbot_env
```
4. Installer rasa :
``` bash
pip install rasa
```

