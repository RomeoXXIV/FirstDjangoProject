# FirstDjangoProject

Ce dépôt contient le code source pour 'First Django Project'. Il s'agit de ma première application web construite avec le framework Django pour Python.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé Python et `pip` sur votre machine. Django est compatible avec Python 3.8, 3.9, et 3.10. Vous pouvez télécharger Python depuis le [site officiel](https://www.python.org/downloads/).

## Configuration de l'Environnement de Développement

Pour mettre en place votre environnement de développement, suivez ces étapes :

### Cloner le dépôt

Pour cloner le dépôt sur votre machine locale, exécutez la commande suivante :

```bash
git clone https://github.com/username/nom-du-projet-django.git
cd nom-du-projet-django
```

### Créer un environnement virtuel

Exécutez l'une des commandes suivantes en fonction de votre système d'exploitation :

- Sur Windows :

  ```cmd
  python -m venv env
  ```

- Sur macOS et Linux :

  ```bash
  python3 -m venv env
  ```

### Activer l'environnement virtuel

- Sur Windows :

  ```cmd
  .\env\Scripts\activate
  ```

- Sur macOS et Linux :

  ```bash
  source env/bin/activate
  ```

### Installer les dépendances

Installez toutes les dépendances nécessaires en exécutant :

```bash
pip install -r requirements.txt
```

### Configurer Django

1. Mettez en place la base de données initiale :

   ```bash
   python manage.py migrate
   ```

2. Créez un superutilisateur pour l'administration de Django :

   ```bash
   python manage.py createsuperuser
   ```

3. Lancez le serveur de développement :

   ```bash
   python manage.py runserver
   ```

4. Ouvrez un navigateur et accédez à `http://127.0.0.1:8000` pour voir l'application en action.

## Tests

Pour exécuter les tests, utilisez la commande suivante :

```bash
python manage.py test
```

## Déploiement

Les instructions de déploiement varient selon l'environnement de production. Veuillez consulter la documentation de déploiement de Django pour plus d'informations.

## Contribuer

Les contributions à ce projet sont les bienvenues. Veuillez consulter les [instructions de contribution](CONTRIBUTING.md) pour plus d'informations sur la soumission de pull requests.

## Licence

Ce projet est sous licence MIT. Veuillez consulter le fichier [LICENSE](LICENSE) pour plus d'informations.

N'oubliez pas de remplacer `https://github.com/username/nom-du-projet-django.git` par l'URL de votre dépôt Git et `Nom du Projet Django` par le nom réel de votre projet. Vous devriez également ajouter des fichiers `CONTRIBUTING.md` et `LICENSE` pour fournir des informations supplémentaires sur la manière de contribuer au projet et sur les termes de la licence sous laquelle il est distribué.