
PROJET 6 : Construire une API sécurisée

Hot Takes par Piiquante

Objectif : développer une application web de critique de sauces piquantes, ayant pour but de permettre aux utilisateurs de télécharger leurs sauces piquantes préférées et de liker ou disliker celles que les autres partagent

-------------------------------------------

* Pour démarrer le projet * 

1. Cloner le frontend fourni à cette adresse : https://github.com/OpenClassrooms-Student-Center/Web-Developer-P6
2. Ouvrir un terminal (Linux/Mac) ou une invite de commande/PowerShell (Windows)
3. Exécuter la commande npm install et npm install nodemon à partir du répertoire du projet
4. À partir du dossier frontend, lancer la commande npm start
5. Créer ensuite dans votre répertoire initial le dossier backend
6. À partir du dossier backend, lancer la commande npm init pour initaliser un nouveau projet Node 
7. À partir du dossier backend, lancer la commande nodemon server
8. À partir du dossier backend, on initialise un repo git et on créé un fichier .gitignore (dans lequel on y mettra le dossier images, le fichier .env et le dossier node_modules)
9. Dans ce même dossier, créer un dossier images (qui contiendra toutes les images utilisées pour les créations/modifications de sauces)

------------------------------------------

Ce projet utilise .dotenv pour protéger les mots de passes et le token appelé dans le code. Il faut donc créer un fichier .env à la racine du dossier backend et renseigner les lignes suivantes :
MONGO_ACCESS = "insérer ici l'adresse d'accès à la base de données que vous souhaitez utiliser"
SECRET_TOKEN = "insérer ici un token aléatoire"

La base de données utilisée pour ce projet est MongoDB

------------------------------------------

* Précisions *

Le frontend se lance à l'adresse http://localhost:4200/
Le backend se lance à l'adresse http://localhost:3000/ 