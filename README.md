# 🎓 Système de Gestion Universitaire

## 📌 Présentation

Ce système est une plateforme web complète et sécurisée destinée à gérer les aspects académiques de l’Université Oran 1 Ahmed Ben Bella. Il fournit des interfaces dédiées pour les **administrateurs**, **enseignants** et **étudiants**, permettant une gestion fluide des utilisateurs, des modules et des notes.

---

## 🧩 Fonctionnalités

### 🔐 Authentification Sécurisée

* Connexion par rôle (Admin, Enseignant, Étudiant)
* Mots de passe hachés
* Redirection automatique selon le profil

### 🛠️ Espace Administrateur

* Tableau de bord centralisé
* Gestion des :

  * Comptes enseignants
  * Comptes étudiants
  * Modules (ajout, suppression, attribution)

### 👨‍🏫 Espace Enseignant

* Accès aux modules attribués
* Saisie des notes (CC et EF)
* Visualisation des résultats étudiants

### 👨‍🎓 Espace Étudiant

* Informations personnelles (matricule, nom, filière, etc.)
* Consultation des notes officielles
* **Calculateur de Moyenne Estimée**

  * Saisie de notes simulées (CC, EF)
  * Ajustement des pourcentages (ex : 40% / 60%)
  * Calcul dynamique avec coefficients des modules

### 🎨 Interface Utilisateur Moderne

* Page de connexion responsive
* Accueil enrichi avec sections :

  * À propos de nous
  * Programmes académiques
  * Vie étudiante
  * Admission
* Logo officiel intégré dans l’en-tête

---

## ⚙️ Technologies

| Côté            | Stack utilisé                          |
| --------------- | -------------------------------------- |
| Frontend        | HTML, CSS, JavaScript                  |
| Backend         | PHP                                    |
| Base de données | MySQL                                  |
| Serveur Web     | Apache / Nginx (XAMPP/WAMP recommandé) |

---

## 🚀 Installation Locale

### ✅ Prérequis

* PHP ≥ 7.4
* Serveur Apache ou Nginx (XAMPP/WAMP)
* MySQL
* Navigateur moderne

### 📅 Étapes d’Installation

1. **Cloner le projet**

   ```bash
   git clone https://github.com/fenneccyber/gestion-universitaire-projet
   ```

   *Ou téléchargez et décompressez l’archive ZIP dans `htdocs` ou `www`.*

2. **Créer la base de données**

   * Nom : `univ_management`
   * Accédez à [phpMyAdmin](http://localhost/phpmyadmin)
   * Créez la base de données nommée `univ_management`
   * Importez le fichier `database_setup.sql` situé à la racine du projet

3. **Configurer le fichier `config.php`**

   ```php
   <?php
   define('DB_SERVER', 'localhost');
   define('DB_USERNAME', 'root');
   define('DB_PASSWORD', '');
   define('DB_NAME', 'univ_management');
   define('SITE_URL', 'http://localhost:8888/');
   ?>
   ```

   * Modifiez `SITE_URL` si le projet est placé ailleurs

4. **Démarrer les services**

   * Lancer Apache et MySQL via XAMPP ou WAMP

5. **Accéder à l’application**

   * Naviguer vers : `http://localhost:8888/`

---

## 🔑 Identifiants par Défaut

### Administrateur

* **Email** : `admin@univ.dz`
* **Mot de passe** : `admin123`

### Enseignants / Étudiants

> À créer depuis le panneau d’administration.

---
# SHOWCASE

![showcase_1](https://github.com/user-attachments/assets/9b5ce422-d0dc-49b4-8207-baba8bc569f2)

![showcase_2](https://github.com/user-attachments/assets/7ab8beb5-0439-41e7-bec0-f74d5c2320ce)

![showcase_3](https://github.com/user-attachments/assets/a5575103-c36d-4230-bcc4-8bb209a9c39d)

![showcase_4](https://github.com/user-attachments/assets/3066ec0f-d4e3-4134-b15e-14d0bbb08816)

![showcase_5](https://github.com/user-attachments/assets/64b873fe-67df-48cd-a192-76cff6375a2c)

![showcase_6](https://github.com/user-attachments/assets/2a484608-253b-4b76-a770-8163c0be731c)

![showcase_7](https://github.com/user-attachments/assets/e92e4c42-21af-43d9-bcec-4aab97417672)

![showcase_8](https://github.com/user-attachments/assets/13c352c3-6113-4689-9e20-7869bc6ed9e8)

![showcase_9](https://github.com/user-attachments/assets/d46a56b2-6267-4375-a886-6290a2c8ee33)

![showcase_10](https://github.com/user-attachments/assets/eff0bb75-dbaa-41d5-9a29-7883306b9a0e)

![showcase_11](https://github.com/user-attachments/assets/d4616941-1285-4584-8cfc-5a3db4357320)

![showcase_12](https://github.com/user-attachments/assets/45af03da-a52e-4f84-be36-2778dcfe3eb2)

![showcase_13](https://github.com/user-attachments/assets/32e5c0b8-c85c-4e94-91c0-c3a7c228b605)

![showcase_14](https://github.com/user-attachments/assets/8fc59fe1-042d-49a2-a72d-acdb2a5c4051)

![showcase_15](https://github.com/user-attachments/assets/1c3178f9-9130-4c5d-8c8e-ddd38bb2efef)

![showcase_16](https://github.com/user-attachments/assets/55d12d60-52e7-4dbf-a6b1-2fb870f1fd43)

![showcase_17](https://github.com/user-attachments/assets/5a2ff7e1-eb59-4751-8ca8-4b53541bcf27)

![showcase_18](https://github.com/user-attachments/assets/073651dc-7668-479c-ac64-ea93e1d7e961)

![showcase_19](https://github.com/user-attachments/assets/e5bbff9e-c09a-43fd-af6c-b4920ddad446)

---
