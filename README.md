# Academy Stats



## Description

Academy Stats est un projet visant à fournir des statistiques éducatives interactives à partir de données open data. Conçu pour les étudiants, enseignants et autres utilisateurs intéressés, il permet de filtrer, analyser et visualiser des données à travers des rapports dynamiques et adaptés.

## Fonctionnalités principales

Extraction et nettoyage des données : Les données sont récupérées via Talend, nettoyées et stockées dans une base de données.

Visualisation interactive : Les rapports sont créés à partir des données via Power BI et publiés pour un accès facile.

Publication et intégration : Les rapports sont intégrés au site web et accessibles directement aux utilisateurs.

Filtres personnalisés : Les utilisateurs peuvent appliquer des filtres avancés pour obtenir des statistiques précises.

### Technologies utilisées

Frontend : HTML5, CSS3, JavaScript

Backend : Python

Base de données : MySQL

Outils ETL : Talend

Visualisation : Power BI (periode d'essai) 

## Installation

### Prérequis

### Outils nécessaires :

Python 3.x

Talend (pour le traitement ETL)

MySQL

Power BI Desktop

### Dépendances Python :

pandas

numpy

flask (ou tout autre framework backend utilisé)

### Étapes

Clonez le dépôt depuis GitHub :

git clone https://github.com/Fjsksksk/Academy-Stats.git

Installez les dépendances Python :

pip install -r requirements.txt

Configurez la base de données MySQL :

Importez les données nettoyées dans la base via Talend.

Lancez le serveur backend :

python app.py

Ouvrez votre navigateur et accédez à l'URL : http://localhost:5000

## Utilisation

Extraction des données : Talend est utilisé pour connecter les sources de données (ex : fichiers CSV) et effectuer le nettoyage.

Visualisation des rapports :

Les rapports Power BI sont liés à la base de données pour générer des visualisations interactives.

Publiez les rapports sur votre espace de travail Power BI.

## Intégration :

Récupérez les liens des rapports et intégrez-les au site web via des iframes ou des APIs.

Accès utilisateurs :

Les utilisateurs peuvent appliquer des filtres pour personnaliser les données affichées sur les rapports.

Contributions

Les contributions sont les bienvenues pour améliorer ce projet.

Comment contribuer

Forkez le dépôt GitHub.

Créez une branche pour votre fonctionnalité :

git checkout -b ma-fonctionnalite

Effectuez vos modifications et testez-les.

Soumettez une pull request avec une description claire des modifications.

## Licence

Ce projet est sous licence MIT.

Remerciements

Merci à Candice Giami et Thanina Benmammar pour leur collaboration et vision dans la réalisation de ce projet.


