# Projet-JS---Gestion-du-Restaurant FTH

# Projet de Restaurant FTH

Ce projet est une application web complète pour un restaurant, gérant les aspects client et administrateur.  Il utilise HTML, CSS, JavaScript et une API Mock pour simuler les données.

## Fonctionnalités

**Côté Client:**

* **Page d'accueil (Untitled-1.html):** Affiche une présentation du restaurant, le menu, le panier d'achat et les avis clients.  Intègre un système de panier fonctionnel avec ajout, suppression et calcul du total.  Permet la commande seulement si l'utilisateur est connecté.
* **Page de connexion (Page 1.html):**  Permet aux clients de se connecter avec leur email et mot de passe.  Un système d'inscription est également disponible.
* **Gestion du profil client:** Affichage des informations du client connecté.
* **Déconnexion:** Permet au client de se déconnecter.
* **Système d'avis:** Affichage des avis clients.


**Côté Administrateur:**

* **Page d'administration (Page admine.html):**  Permet à l'administrateur d'ajouter, de modifier, de supprimer et d'afficher les plats du menu.  L'interface utilise une liste interactive et un formulaire.


## Technologies Utilisées

* **Frontend:** HTML, CSS, JavaScript, SweetAlert2 (pour les messages d'alerte)
* **Backend Simulé:** API Mock (https://676c6bee0e299dd2ddfcc682.mockapi.io/restaurant/resto)  -  Note:  Ceci est une API de test.  Pour une application réelle, un backend approprié serait nécessaire.
* **Stockage Local:** localStorage (pour les données client)


## Installation et Exécution

1. **Cloner le dépôt:**  
   ```bash
   git clone https://github.com/salma518/FTH-Restaurant.git
   ```
2. **Ouvrir les fichiers HTML:** Ouvrez les fichiers `Untitled-1.html`, `Page 1.html`, et `Page admine.html` dans un navigateur web.


## Structure des Fichiers

* `index.html` (ou `Untitled-1.html`): Page d'accueil client.
* `Page 1.html`: Page de connexion/inscription client.
* `Page admine.html`: Page d'administration.
* `style.css`:  Feuille de style pour la page d'accueil et les pages clients.
* `style2.css`: Feuille de style pour la page de connexion/inscription.
* `admine.css`: Feuille de style pour la page d'administration.
* `script.js`:  Script JavaScript pour la page d'accueil et les pages clients.
* `admine.js`: Script JavaScript pour la page d'administration.
* `Validation.js`: Script JavaScript pour la validation des formulaires.


##  Contact

Pour toute question, contactez-nous par email à salma.fathi16000@gmail.com



