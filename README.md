# Groupomania
Groupomania Social Network: projet frontend et backend.

CONDITIONS PRÉALABLES

Ce projet utilise NodeJs 14.15.3, Express 4.17.1 et MySQL 5.7.10 pour le backend, et @ vue / cli 4.5.9 pour le frontend. Vous devrez avoir Node, MySQL et Vue CLI installés localement sur votre machine.

INSTALLATION

Veuillez cloner ce référentiel: il vous fournira les deux dossiers nécessaires: backend et frontend.

ACCÈS À LA BASE DE DONNÉES

Cette application utilise le plugin dotenv pour masquer les données de connexion. Dans le dossier du backend, vous trouverez un fichier ".env-evaluator", qui vous donnera accès à la base de données MySQL groupomania, une fois remplie avec les bonnes valeurs. Pour le faire fonctionner, veuillez changer son nom en ".env" et remplir les valeurs avec "DB_USER" et "DB_PASS" fournis séparément.

En outre, vous devez créer localement la base de données. Dans le dossier backend que vous avez cloné, saisissez: 'mysql -u "DB_USER" -p'. Puis mot de passe = "DB_PASS" (bien sûr, remplacez "DB_USER" et "DB_PASS" par les données correctes). Sur la ligne suivante, vous devez copier / coller tout le contenu du fichier "db.sql" (situé dans le dossier "backend / db"). Pour éviter toute erreur dans la construction de la base de données, il est préférable de copier-coller paragraphe après paragraphe (d'abord «Section de réinitialisation et de création», puis «Section de création de tables», puis «Section entrées» puis «Section clés étrangères»). Votre base de données groupomania est créée.

Lancez l'application

Vous aurez besoin de deux fenêtres de terminal: une pour le frontend, une pour le backend. Sur le terminal frontal: lancez "npm install" (ou "sudo npm install" sur Mac) pour installer tous les plugins nécessaires, puis "npm run serve". Le frontend de l'application est visible sur http: // localhost: 8080 /. Sur le terminal backend: lancez "npm install" (ou "sudo npm install" sur Mac), puis "node server" ou "nodemon server.js". Le serveur doit fonctionner sur localhost avec le port par défaut 3000.
