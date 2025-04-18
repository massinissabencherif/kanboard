📌 Kanboard - Application de Gestion de Projet  

📝 Présentation  
Kanboard est une application web de gestion de projet basée sur le principe Kanban. Elle permet aux utilisateurs de créer et d'organiser des projets collaboratifs avec un système de gestion des tâches avancé.  

---

🎯 Objectifs  
- Développer une application web responsive et mobile-friendly.  
- Implémenter une gestion des projets et des tâches sous forme de Kanban.  
- Offrir une expérience utilisateur fluide avec authentification, affichage dynamique et collaboration en temps réel.  
- Fournir une conteneurisation complète (Docker) et un suivi Git rigoureux.  

---

🚀 Fonctionnalités Principales  

🌍 Visibilité (1 pt)  
- Déploiement sur Internet avec un nom de domaine sécurisé et un bon référencement SEO.  

🏗️ Gestion des Projets (5 pts)  
- Inscription & Connexion : Création de compte avec validation par email.  
- Création de Projets : Un utilisateur peut créer un projet et inviter des membres.  
- Gestion des Membres : Seul le créateur peut ajouter ou retirer des membres par email.  
- Gestion des Tâches : Chaque tâche peut être attribuée à un ou plusieurs membres.  

✅ Gestion des Tâches (2 pts)  
- Une tâche contient :  
  - Titre  
  - Description (optionnelle)  
  - Catégorie (colonne Kanban : marketing, dev, etc.)  
  - Priorité (basse, moyenne, élevée)  
  - Date de création  
  - Date de complétion & échéance  

👀 Affichage des Tâches (2 pts)  
- Vue Kanban : Organisation des tâches en colonnes avec glisser-déposer.  
- Vue Liste : Recherche et filtrage rapide des tâches.  
- Vue Calendrier : Affichage des tâches selon leur date d’échéance.  

🎨 Design & Expérience Utilisateur (1 pt)  
- Interface moderne et responsive, adaptée aux thèmes clair/sombre.  

💻 Technologies Utilisées (2 pts)  
- Front-end : HTML, CSS, JavaScript  
- Back-end : Laravel (PHP)  
- Base de données : SQL  

🔄 Gestion du Code & Conteneurisation (4 pts)  
- Git : Historisation avec commits clairs et contributions suivies.  
- Docker : Conteneurisation complète pour faciliter le déploiement.  

---

🎁 Bonus (5 pts)  

📶 Mode Hors-Ligne (2 pts)  
- Gestion des modifications hors connexion, avec synchronisation automatique au retour du réseau.  

⚡ Temps Réel (1 pt)  
- Mise à jour instantanée des modifications et notifications en live (Laravel Pusher, Echo, Mercure).  

📊 Statistiques & Rapports (1 pt)  
- Analyse des tâches : taux d’achèvement, répartition par catégorie, performance des membres.  

📅 Synchronisation iCal (1 pt)  
- Exportation des tâches au format iCal pour synchronisation avec Google Calendar, Outlook, etc.  

---

📌 Contraintes & Livrables  
✔️ Projet soumis sous format ZIP (pas de lien Git).  
✔️ Tous les membres doivent être capables d’expliquer le code.  
✔️ Respect des bonnes pratiques de développement (nommage, documentation, commits clairs).  
✔️ Soutenance professionnelle : présentation soignée et argumentée.  

---

📅 Calendrier  
Séance | Objectif  
--------|----------  
1 | Lancement du projet annuel  
2 | Validation des groupes  
3 | Suivi de projet  
4 | Suivi de projet  
5 | Démonstration finale  

---

🚀 Kanboard est conçu pour offrir une expérience de gestion de projet fluide, collaborative et intuitive. Prêt à organiser tes tâches efficacement ? 🎯  

Pour mettre en place l'environnement : 

mkdir kanboard
cd kanboard   
composer global require laravel/installer 
laravel new kanboard-back  
cd kanboard-back        
npm install && npm run build  
composer run dev 
composer require laravel/sail --dev  
php artisan sail:install        
./vendor/bin/sail up   
./vendor/bin/sail artisan migrate    
./vendor/bin/sail composer require laravel/breeze --dev
./vendor/bin/sail artisan breeze:install  
./vendor/bin/sail artisan migrate   
./vendor/bin/sail npm install    
./vendor/bin/sail npm run dev                          
