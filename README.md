# Task Manager App

Bienvenue sur le projet **Task Manager App**, une application complète de gestion de tâches développée dans le cadre de ma formation Concepteur Développeur d'Applications (CDA).

Ce dépôt est organisé de manière découplée, regroupant l'API (Back-end) et le Client (Front-end) dans un seul espace de travail pour faciliter la maintenance et la présentation du projet.

---

## 🏗️ Architecture du Projet

Le projet est divisé en deux parties distinctes :

*   **`/api`** : Le serveur Back-end développé avec **NestJS**. Il gère la logique métier, la base de données, la sécurité et l'authentification.
*   **`/client`** : L'interface utilisateur Front-end développée avec **Next.js**. Elle offre une expérience fluide, moderne et réactive.

---

## 🛠️ Technologies Utilisées

### Back-end (`/api`)
*   **Framework :** NestJS (TypeScript)
*   **Base de données :** [Ex: PostgreSQL / MongoDB / MySQL]
*   **ORM :** [Ex: Prisma / TypeORM]
*   **Sécurité :** Authentification JWT

### Front-end (`/client`)
*   **Framework :** Next.js (React / TypeScript)
*   **Styles :** [Ex: Tailwind CSS / Shadcn/ui]
*   **Gestion d'état :** [Ex: Context API / Zustand]

---

## 🚀 Installation et Lancement

Pour lancer ce projet en local, suivez les instructions ci-dessous.

### Prérequis
*   Node.js (Version 18 ou supérieure)
*   Un gestionnaire de paquets (NPM ou Yarn)

### 1. Cloner le projet
```bash
git clone [https://github.com/ton-pseudo/task-manager-app.git](https://github.com/ton-pseudo/task-manager-app.git)
cd task-manager-app
``` 

### 2. Lancer le Back-end
```bash
cd api
npm install
npm run start:dev
```
Le serveur se lance généralement sur le port http://localhost:3000.

### 3. Lancer le Front-end
```bash
# Ouvrez un nouveau terminal à la racine du projet
cd client
npm install
npm run dev
```
L'application est accessible sur http://localhost:3000 (ou 3001 si conflit).

## 📝 Fonctionnalités (En cours de développement)

[ ] Inscription et Connexion sécurisée (Auth JWT)

[ ] Création, modification et suppression de tâches (CRUD)

[ ] Filtrage des tâches par statut (À faire / En cours / Terminé)

[ ] Interface responsive (Mobile / Desktop)

## 👤 Contact

Sylvie HOAREAU

    LinkedIn : [Lien vers mon profil]

    Portfolio : [Lien vers mon portfolio]


