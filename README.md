SNELControl - Plateforme de Gestion Électrique à Distance (RDC)

SNELControl est une application web moderne conçue pour les agents de la SNEL (Société Nationale d'Électricité) en République Démocratique du Congo. Elle permet de couper et rétablir l’électricité à distance, client par client, tout en offrant un tableau de bord simple et puissant.


---

Fonctionnalités

Visualisation des clients par zone géographique

Suivi du statut électrique : Alimenté / Coupé

Contrôle à distance (simulation locale)

Interface intuitive, rapide et compatible mobile



---

Déploiement local

Prérequis

Node.js >= 16

npm ou yarn


Installation

npm install
npm run dev

Accéder à l’application sur : http://localhost:5173


---

Structure du projet

snelcontrol/
├── public/
│   └── index.html
├── src/
│   ├── SnelDashboard.jsx
│   ├── index.jsx
│   └── index.css
├── package.json
├── README.md


---

Déploiement sur Vercel

1. Créer un compte sur vercel.com


2. Connecter ce dépôt GitHub


3. Cliquer sur "Import Project" > sélectionner snelcontrol


4. Vercel détecte React + Vite automatiquement


5. Le site est déployé en quelques secondes




---

À propos

Ce projet a été conçu avec React, Vite, Framer Motion et shadcn/ui pour une UX moderne. Développé avec l’assistance de ChatGPT pour un usage professionnel par la SNEL.


---

Licence

Libre d’usage, amélioration et adaptation sous licence MIT.
