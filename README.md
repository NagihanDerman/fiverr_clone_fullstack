# 🎯 Clone de Fiverr - Application Web Full Stack

Ce projet est un **clone de la plateforme de services Fiverr**. Les utilisateurs peuvent vendre, acheter des services, discuter entre eux et gérer leurs profils. Il s'agit d'une application full-stack moderne construite avec les technologies web actuelles.

---

## ✨ Fonctionnalités

- Authentification des utilisateurs (JWT + Cookie)
- Comptes vendeurs et acheteurs
- Création, modification et affichage de services (gigs)
- Système de messagerie en temps réel
- Création et gestion des commandes
- Évaluations et commentaires
- Téléchargement d’images via Cloudinary
- Design responsive compatible mobile (TailwindCSS)
- Navigation multi-pages (React Router)
- Optimisation des performances avec React Query

---

## 🧩 Technologies et bibliothèques utilisées

### 🖥️ Frontend (React)

- **React** – Pour construire l’interface utilisateur
- **React Router DOM** – Pour la navigation entre les pages
- **React Icons** – Pour les icônes vectorielles
- **React Toastify** – Notifications et alertes utilisateur
- **@tanstack/react-query** – Gestion des requêtes API et cache
- **@splidejs/react-splide** – Composants de carrousel/slider
- **Axios** – Requêtes HTTP
- **Moment** – Formatage des dates
- **Tailwind CSS** – Framework CSS moderne

### ⚙️ Backend (Node.js + Express)

- **Express** – Serveur web
- **MongoDB + Mongoose** – Base de données NoSQL
- **jsonwebtoken (JWT)** – Authentification par jetons
- **Bcrypt** – Hashage de mots de passe
- **Dotenv** – Variables d’environnement
- **Cors** – Autorisations Cross-Origin
- **Cookie-parser** – Gestion des cookies
- **Multer** – Téléversement de fichiers (form-data)
- **Cloudinary SDK** – Téléversement d’images sur le cloud

---

## 🚀 Installation

### Prérequis :
- Node.js (v18+)
- MongoDB (local ou via Atlas)
- Git

### 1. Backend

```bash
cd backend
npm install
npm run dev


### GIF
<img src="./Frontend/fiverr_clone.gif"/>
