# Tableau-de-bord-dynamique-pour-l-valuation-des-performances-des-nanosatellites-KSF-Space


##  Description  

Ce projet est une **application d’aide à la décision** permettant de mesurer et d'analyser la **performance des nanosatellites** via un **tableau de bord interactif et dynamique**.  
Développée dans le cadre d’un projet chez **KSF Space**, l’application fournit des outils de visualisation avancés pour surveiller les satellites en fonction de plusieurs **indicateurs clés**.  

 **Objectif principal :**  
Offrir une **solution web** qui collecte, traite et affiche les données des nanosatellites, facilitant ainsi l'analyse et la prise de décision.  

---

## Fonctionnalités  

 **Importation et mise à jour des données** des nanosatellites  
 **Visualisation interactive des indicateurs clés** sous forme de graphiques dynamiques  
 **Exploration et filtrage des données** selon différents critères  
 **Statistiques avancées et analyses prédictives**  
 **Interface intuitive et ergonomique**  
 **Accès sécurisé avec authentification**  

---

## 🛠Technologies utilisées  

| Technologie | Utilisation |
|------------|------------|
| **Python** | Backend & Traitement des données |
| **Flask** | Framework Web |
| **HTML / CSS / Bootstrap** | Interface utilisateur |
| **JavaScript / Chart.js** | Visualisation de données |
| **MySQL** | Base de données |
| **Pandas & NumPy** | Analyse et manipulation des données |
| **Web Scraping** | Collecte automatique des données |
| **Power AMC** | Modélisation de la base de données |

---

## 📂 Structure du projet  

📂 project-root/ 
│── 📁 static/ # Fichiers CSS, JS et assets 

│── 📁 templates/ # Pages HTML

│── 📁 data/ # Données des nanosatellites

│── 📁 models/ # Scripts de modélisation et analyse

│── app.py # Code principal Flask 

│── config.py # Fichier de configuration

│── database.sql # Script de création de la base de données 

│── requirements.txt # Dépendances du projet 

│── README.md # Documentation du projet


---

##  Installation et Exécution  

### Prérequis  

Avant de commencer, assurez-vous d'avoir installé :  
- **Python 3.x**  
- **MySQL**  
- **Git**  

###  Étapes d’installation  

1. **Clonez le dépôt** :  
   ```bash
   git clone https://github.com/votre-repo.git
   cd votre-repo

    Installez les dépendances :

pip install -r requirements.txt

Configurez votre base de données MySQL :

    Importez le fichier database.sql pour créer les tables nécessaires.

Lancez l’application :

    python app.py

    Accédez à l’application :
    
        Ouvrez un navigateur et allez sur : http://127.0.0.1:5000/

Indicateurs de Performance

Indicateurs disponibles dans le tableau de bord :

1  Distribution des nanosatellites par année

2 Répartition des organisations et nations impliquées

3 Évolution de la mise à jour des nanosatellites

4 Répartition des catégories et des licences

5 Nombre total de missions par période

6 Répartition des niveaux de mission (national, régional, etc.)

7 Statut des nanosatellites (opérationnel, en panne, etc.)

📜 API Endpoints

L’application propose plusieurs API REST pour l’exploitation des données :
Méthode	Endpoint	Description

GET	/api/nanosatellites	Récupérer toutes les données des nanosatellites

GET	/api/nanosatellites/{id}	Obtenir les détails d’un nanosatellite spécifique

POST	/api/nanosatellites	Ajouter un nouveau nanosatellite

PUT	/api/nanosatellites/{id}	Mettre à jour un nanosatellite

DELETE	/api/nanosatellites/{id}	Supprimer un nanosatellite

🖥️ Interfaces de l’application

 Pages principales :

    Page d’accueil : Présentation du projet et accès aux fonctionnalités
    
    Page de connexion : Authentification des utilisateurs
    
    Tableau de bord : Visualisation des indicateurs clés
    
    Gestion des nanosatellites : Ajout, modification et suppression

Aperçu des interfaces :

 Déploiement
 
🔹 Déploiement local

Utilisation de Flask avec Gunicorn et un serveur MySQL :

gunicorn -w 4 -b 0.0.0.0:5000 app:app

🔹 Déploiement sur un serveur cloud (ex: AWS, Heroku)

    Configurer un serveur cloud avec un environnement Python
    
    Déployer le projet avec Docker ou Heroku
    
    Configurer un serveur de base de données distant (ex: Amazon RDS ou Google Cloud SQL)

👨‍💻 Contributeurs

🔹 Idrissi Mounadi Doha

📍 Encadré par : Pr. Rachid Dehbi

 Améliorations futures

🔹 Ajout de prédictions avec Machine Learning sur la performance des nanosatellites

🔹 Automatisation complète de la collecte et mise à jour des données

🔹 Intégration avec d’autres bases de données spatiales (NASA, ESA, etc.)

🔹 Amélioration de l’interface utilisateur avec React.js

📜 Licence

Ce projet est sous licence MIT. Vous êtes libre de l’utiliser et de le modifier.

 
Ce projet vise à optimiser la gestion des nanosatellites grâce à une approche data-driven et une interface interactive.
 Toute contribution est la bienvenue !


 # MERCIIIIIIIIIIIII !!!!!!!!!!!


---

