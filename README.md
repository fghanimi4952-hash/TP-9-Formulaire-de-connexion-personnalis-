
# name: "TP – Spring Security Login Form"
## description: 
  Ce projet montre comment créer une page de connexion personnalisée
  avec Spring Security, gérer l’authentification, les rôles (USER/ADMIN),
  la redirection et la protection des routes.

##  Objectifs du Projet

Ce TP vise à comprendre et personnaliser le mécanisme d’authentification de Spring Security.
L’objectif est de remplacer la page de connexion par défaut de Spring par un formulaire HTML personnalisé, tout en gérant :

les erreurs de connexion,
les redirections après authentification,
la déconnexion,
et la différenciation des accès selon les rôles.
Ce TP fait suite au TP (authentification en mémoire) et introduit la notion de flux d’authentification contrôlé par l’application.

##  Structure du Projet :
<img width="574" height="745" alt="image" src="https://github.com/user-attachments/assets/13cbe45d-4cf9-4a06-821f-07eee5d26642" />




## 🔎 Pages à Tester (localhost)

http://localhost:8080/login

http://localhost:8080/login?error=true

http://localhost:8080/login?logout=true

http://localhost:8080/home

http://localhost:8080/user/dashboard

http://localhost:8080/admin/dashboard

http://localhost:8080/logout

## ▶️ Comment Lancer le Projet

Importer le projet dans IntelliJ IDEA

Vérifier l'installation de Java 21

Exécuter l’application via :
Run → Run SecurityLoginApplication

Accéder à l’application via :
http://localhost:8080/login


https://github.com/user-attachments/assets/de3be748-4848-44dc-bcb1-73fd92c6fc3c

 ## Auteur
Jamila Dabachine
Master : Technologies Émergentes en Éducation – ENS Marrakech
Année : 2025
