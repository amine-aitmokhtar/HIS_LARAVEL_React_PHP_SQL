# HIS University

**Période du projet : Février 2022 - 13 Juillet 2023**

## Description

Ce projet consiste en une application web pour la gestion des inscriptions en ligne et le suivi des étudiants. L'application permet de simplifier et d'automatiser le processus d'inscription et de suivi des dossiers étudiants, offrant une solution efficace et intuitive pour les universités.

## Environnements

- **Frontend** : React, jQuery, CSS
- **Backend** : Laravel
- **Base de données** : MySQL

## Fonctionnalités

- **Gestion des inscriptions** : Inscription en ligne des étudiants avec un suivi en temps réel.
- **Suivi des étudiants** : Gestion des dossiers étudiants, incluant les informations académiques et administratives.
- **Tableau de bord** : Interface intuitive pour les administrateurs permettant de gérer et de visualiser les données.
- **Notifications** : Système de notifications pour les mises à jour et les rappels importants.

## Installation et configuration

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/your-username/HIS-University.git
   ```

2. Naviguer vers le répertoire du projet :
   ```bash
   cd HIS-University
   ```

3. Installer les dépendances du frontend :
   ```bash
   cd frontend
   npm install
   ```

4. Installer les dépendances du backend :
   ```bash
   cd backend
   composer install
   ```

5. Configurer la connexion à la base de données dans le fichier `.env`.

6. Exécuter les migrations et les seeders pour configurer la base de données :
   ```bash
   php artisan migrate --seed
   ```

7. Lancer les serveurs de développement :
   ```bash
   npm start
   ```
   ```bash
   php artisan serve
   ```

## Ressources

- **Documentation React** : [React Documentation](https://reactjs.org/docs/getting-started.html)
- **Documentation jQuery** : [jQuery Documentation](https://api.jquery.com/)
- **Documentation Laravel** : [Laravel Documentation](https://laravel.com/docs/)
- **Documentation MySQL** : [MySQL Documentation](https://dev.mysql.com/doc/)
