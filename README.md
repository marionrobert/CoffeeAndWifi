# Application de Collecte de Données de Cafés

## Introduction
Ce projet consiste à créer une application web simple permettant aux utilisateurs d'ajouter des informations sur les cafés, telles que le nom du café, l'emplacement sur Google Maps, les horaires d'ouverture et de fermeture, ainsi que des évaluations sur la qualité du café, la force du wifi et la disponibilité des prises électriques. Les données sont stockées dans un fichier CSV (`cafe-data.csv`) agissant comme une base de données simulée.

## Fonctionnalités
- Affiche la liste des cafés ajoutés avec leurs informations correspondantes.
- Permet aux utilisateurs d'ajouter de nouveaux cafés avec des détails spécifiques.

## Exigences
- Python 3.x
- Flask: Ce projet utilise Flask comme framework web pour Python.
- Flask-Bootstrap: Les templates HTML utilisent Flask-Bootstrap pour des fonctionnalités Bootstrap intégrées.
- Flask-WTF, WTForms: gestion des formulaires dans l'application

## Installation et Configuration
1. Assurez-vous d'avoir Python installé sur votre système.
2. Installez les packages requis en utilisant pip et le fichier `requirements.txt`: `pip install -r requirements.txt`.
3. Placez les fichiers de templates (`add.html`, `cafes.html`, `index.html`) dans un répertoire nommé `templates`.
4. Assurez-vous d'avoir un navigateur Chrome installé sur votre système.
5. Téléchargez le Chrome WebDriver compatible avec la version de votre navigateur Chrome et configurez la variable d'environnement `CHROME_DRIVER_PATH` avec le chemin vers l'exécutable Chrome WebDriver.
6. Exécutez le script `main.py` pour démarrer l'application Flask.

## Utilisation
1. Accédez à l'URL fournie par Flask dans votre navigateur.
2. Sur la page d'accueil, vous pouvez naviguer vers la page qui liste les cafés les détails des cafés déjà enregistrés.
3. Depuis la page de visionnage de tous le scafés, vous pouvez naviguer vers l'accueil ou vers la page d'ajout de café pour soumettre de nouvelles entrées.
4. Sur la page d'ajout d'un nouveeau café, vous pouvez remplir les champs du fomrulaire pour enregistrer un nouveua café.
   - concernant le champ "URL" : vous devez renseigner le lien de partage du lieu (ne comprenant pas de ","): ![image](https://github.com/marionrobert/CoffeeAndWifi/assets/107509668/88e29744-9d54-4610-8ec4-a22d7b5bcf77)


## Structure du Projet
- `main.py`: Le script principal de l'application Flask.
- `templates/`: Répertoire contenant les fichiers HTML pour les pages web.
    - `add.html`: Formulaire d'ajout de café.
    - `cafes.html`: Affichage de la liste des cafés.
    - `index.html`: Page d'accueil.
- `cafe-data.csv`: Fichier CSV simulé agissant comme base de données pour stocker les informations des cafés renseignés par l'utilisateur lrosqu'il ajoute un nouveua acfé.
- `requirements.txt`: Fichier contenant la liste des packages Python nécessaires pour l'application.

## Interfaces
### index.html
![image](https://github.com/marionrobert/CoffeeAndWifi/assets/107509668/a334f035-dad9-456d-bf48-582085f08989)
### cafes.html
![image](https://github.com/marionrobert/CoffeeAndWifi/assets/107509668/a443800e-efe5-4323-a5ae-e2861352bc58)
### add/html
![image](https://github.com/marionrobert/CoffeeAndWifi/assets/107509668/9d86f45d-7611-4cf8-971e-6207d029caba)


## Remarques
- Assurez-vous de configurer les variables d'environnement et les chemins appropriés selon votre configuration système.
- Assurez-vous que la version de Chrome WebDriver utilisée est compatible avec la version de Chrome installée sur votre système.
- Ce projet a été réalisé dans le cadre du cours [100 Days of Code: The Complete Python Pro Bootcamp](https://www.udemy.com/course/100-days-of-code/) d'Angela Yu sur la plateforme Udemy.
