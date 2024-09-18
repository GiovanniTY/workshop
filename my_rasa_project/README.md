# Documentation du Projet Chatbot

Bienvenue dans le projet de chatbot ! Ce document fournit des instructions pour cloner le dépôt, configurer l'environnement et exécuter le modèle.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les outils suivants :

- [Python](https://www.python.org/downloads/) (version 3.8 ou ultérieure)
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
Créer un environnement virtuel avec Conda :

``` bash
conda create --name chatbot_env python=3.8
```
Activer l'environnement :
```bash
conda activate chatbot_env
```
Installer rasa :
``` bash
pip install rasa
```
## Option 2 : Utiliser un Environnement Python Standard

1. Accédez au répertoire du projet :
```bash
cd nom_de_repertoire

```
2. python -m venv chatbot_env

```bash
python -m venv chatbot_env
```

3. Activer l'environnement :

-Sur Windows :

```bash
chatbot_env\Scripts\activate
```
-Sur macOS/Linux :

```bash
 source chatbot_env/bin/activate
```

# Configuration du Projet

## Configurer le fichier `config.yml` :

Le fichier `config.yml` définit la configuration des composants NLU et des politiques de dialogue. Vous pouvez ajuster ces paramètres en fonction des besoins de votre projet.

## Définir les Intents et les Réponses :

Les intents et les réponses sont définis dans le fichier `domain.yml`. Vous pouvez ajouter, modifier ou supprimer des intents et des réponses selon les exigences de votre bot.

## Ajouter des Données d'Entraînement :

Les données d'entraînement pour la NLU et les dialogues sont stockées dans les fichiers `nlu.yml` et `stories.yml`. Assurez-vous que ces fichiers contiennent des exemples pertinents pour les scénarios que vous souhaitez couvrir.

## Configurer les Points de Fin :

Le fichier `endpoints.yml` permet de configurer les points de fin pour les services externes. Assurez-vous que les URLs et les tokens sont correctement définis.

## Définir les Actions Personnalisées :

Les actions personnalisées sont définies dans le fichier `actions.py`. Ajoutez ou modifiez des actions en fonction des besoins de votre chatbot.


