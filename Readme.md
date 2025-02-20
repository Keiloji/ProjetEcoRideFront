EcoRide est une plateforme web de covoiturage dédiée aux voyageurs soucieux de l'environnement et aux conducteurs proposant des trajets en voiture électrique. Ce site vise à réduire l'empreinte écologique des déplacements individuels tout en offrant une solution économique et conviviale.

Présentation du projet
Le projet EcoRide a débuté le 3 décembre 2024. Malgré les nombreux défis techniques et bugs, j'ai su tirer des leçons de mes erreurs passées pour améliorer ma compréhension du développement web. EcoRide intègre un système de rôles (chauffeur, passager, employé, administrateur), une gestion des crédits (chaque utilisateur reçoit 20 crédits dès son inscription, avec la possibilité d'en ajouter) et un module complet de covoiturage.
La plateforme permet aux visiteurs de rechercher des itinéraires en saisissant une ville de départ, une destination et une date, et d'afficher ensuite une liste de trajets répondant à ces critères. Chaque trajet affiche le pseudo, la photo, la note du chauffeur, le nombre de places restantes, le prix, la date et les horaires, ainsi qu'un bouton « Détail » pour obtenir plus d'informations sur le trajet, le véhicule et les préférences du conducteur.
Le site a été conçu en respectant les meilleures pratiques de développement, de gestion de projet et de versionnement via Git.

Technologies utilisées
Front-end : HTML5, CSS3/SCSS, Bootstrap et JavaScript (avec Chart.js pour les graphiques).
Back-end : PHP avec le framework Symfony, utilisant PDO pour une connexion sécurisée à la base de données.
Base de données : MySQL (MariaDB), avec des structures relationnelles pour gérer les utilisateurs, les trajets, les transactions, etc.
Outils & Déploiement : Git, Composer, VS Code et Heroku pour le déploiement en cloud.
Installation en local
Clonez le dépôt GitHub public.
Installez les dépendances PHP via Composer :

composer install
Créez et configurez votre base de données en important le fichier SQL fourni.
Configurez vos variables d'environnement (fichier .env).
Lancez le serveur Symfony (ou via XAMPP) :

symfony serve
Accédez à l'application via l'URL (ex. http://localhost:8000).
Déploiement sur Heroku
Créez une application sur Heroku .
Configurez les variables d'environnement Heroku (base de données, clés secrètes, etc.).
Poussez votre dépôt vers Heroku :

git push heroku main
Heroku construira l'application automatiquement et vous pourrez accéder au site via l'URL fournie.
Structure du projet
/assets : Fichiers CSS compilés et images.
/src : Code PHP et contrôleurs (back-end).
/public : Point d'entrée du site (index.php).
/js : Scripts JavaScript.
/scss : Fichiers SCSS pour la personnalisation du style.
/templates : Templates Twig (si utilisés).
Gestion de projet
Le projet est géré via Git.

N'hésitez pas à me contacter pour toute question ou suggestion. Merci pour votre intérêt pour EcoRide !
