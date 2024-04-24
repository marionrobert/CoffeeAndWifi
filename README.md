(english below)

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

---
---
# Coffee Data Collection Application

## Introduction
This project aims to create a simple web application allowing users to add information about cafes, such as the cafe name, location on Google Maps, opening and closing hours, as well as ratings on coffee quality, Wi-Fi strength, and availability of electrical outlets. The data is stored in a CSV file (`cafe-data.csv`) acting as a simulated database.

## Features
- Displays the list of added cafes with their corresponding details.
- Allows users to add new cafes with specific details.

## Requirements
- Python 3.x
- Flask: This project uses Flask as the web framework for Python.
- Flask-Bootstrap: HTML templates use Flask-Bootstrap for integrated Bootstrap features.
- Flask-WTF, WTForms: form management in the application

## Installation and Configuration
1. Make sure you have Python installed on your system.
2. Install required packages using pip and the `requirements.txt` file: `pip install -r requirements.txt`.
3. Place the template files (`add.html`, `cafes.html`, `index.html`) in a directory named `templates`.
4. Make sure you have Google Chrome installed on your system.
5. Download the Chrome WebDriver compatible with your Chrome browser version and configure the environment variable `CHROME_DRIVER_PATH` with the path to the WebDriver executable.
6. Run the `main.py` script to start the Flask application.

## Usage
1. Access the URL provided by Flask in your browser.
2. On the homepage, you can navigate to the page listing cafes and their details.
3. From the cafes viewing page, you can navigate back to the homepage or to the add cafe page to submit new entries.
4. On the add cafe page, fill in the form fields to save a new cafe entry.
   - Regarding the "URL" field: you need to provide the place sharing link (excluding commas): ![image](https://github.com/marionrobert/CoffeeAndWifi/assets/107509668/88e29744-9d54-4610-8ec4-a22d7b5bcf77)

## Project Structure
- `main.py`: The main script of the Flask application.
- `templates/`: Directory containing HTML files for web pages.
    - `add.html`: Cafe addition form.
    - `cafes.html`: Display of the list of cafes.
    - `index.html`: Homepage.
- `cafe-data.csv`: Simulated CSV file acting as a database to store cafe information entered by users when adding a new cafe.
- `requirements.txt`: File containing the list of required Python packages for the application.

## Interfaces
### index.html
![image](https://github.com/marionrobert/CoffeeAndWifi/assets/107509668/a334f035-dad9-456d-bf48-582085f08989)
### cafes.html
![image](https://github.com/marionrobert/CoffeeAndWifi/assets/107509668/a443800e-efe5-4323-a5ae-e2861352bc58)
### add.html
![image](https://github.com/marionrobert/CoffeeAndWifi/assets/107509668/9d86f45d-7611-4cf8-971e-6207d029caba)

## Notes
- Ensure to configure environment variables and paths correctly according to your system configuration.
- Make sure the version of Chrome WebDriver used is compatible with the Chrome version installed on your system.
- This project was completed as part of the [100 Days of Code: The Complete Python Pro Bootcamp](https://www.udemy.com/course/100-days-of-code/) course by Angela Yu on the Udemy platform.

