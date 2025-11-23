
# name: "TP – Spring Security Login Form"
## description: >
  Ce projet montre comment créer une page de connexion personnalisée
  avec Spring Security, gérer l’authentification, les rôles (USER/ADMIN),
  la redirection et la protection des routes.

## 🎯 Objectifs du Projet

- Mettre en place un formulaire de connexion personnalisé.
  -Utiliser Spring Security pour gérer l’authentification et les autorisations.
-Définir des rôles (USER et ADMIN) et contrôler l’accès aux pages sensibles.
-Protéger certaines pages et rediriger automatiquement les utilisateurs selon leurs droits.
-Tester l’ensemble des routes en local via localhost.
## 🏗️ Structure du Projet :
<img width="574" height="745" alt="image" src="https://github.com/user-attachments/assets/13cbe45d-4cf9-4a06-821f-07eee5d26642" />

## 🧩 Fonctionnalités Principales

Page de login personnalisée.

Gestion des erreurs de connexion (mot de passe incorrect).

Déconnexion avec message de confirmation.

Redirection automatique après succès ou erreur.

Protection des routes selon le rôle :

Accès réservé ADMIN

Accès réservé USER

Accès commun

Interface simple basée sur Thymeleaf.

## 🛠️ Technologies Utilisées

Java 21

Spring Boot 4

Spring Security 7

Thymeleaf

Maven
## 🔐 Organisation des Pages

/login → Page de connexion

/home → Page d’accueil après authentification

/user/dashboard → Espace réservé aux utilisateurs USER & ADMIN

/admin/dashboard → Espace réservé strictement à ADMIN

/logout → Déconnexion de la session

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
