# Site d'Hommage

Site web dédié aux obsèques avec fonctionnalités interactives pour laisser des messages d'adieu et déposer des fleurs virtuelles.

## Stack Technique

- **Frontend** : HTML5, CSS3, JavaScript (Vanilla)
- **Backend** : Node.js avec Express
- **Base de données** : Fichiers JSON (`.bd`)
- **Hébergement** : Vercel

## Prérequis

- Node.js (version 14 ou supérieure)
- npm

## Installation

```bash
npm install
```

## Démarrage en local

```bash
npm start
```

Le site sera accessible sur `http://localhost:3000`

## Déploiement sur Vercel

### Option 1 : Via l'interface Vercel

1. Allez sur [vercel.com](https://vercel.com)
2. Connectez votre compte GitHub/GitLab/Bitbucket
3. Importez votre projet
4. Vercel détectera automatiquement la configuration

### Option 2 : Via la CLI

```bash
npm install -g vercel
vercel
```

Suivez les instructions à l'écran pour finaliser le déploiement.

## Structure du projet

- `index.html` - Page principale
- `style.css` - Styles CSS
- `server.js` - Serveur Express avec API
- `adieu.bd` - Base de données des messages
- `fleur.bd` - Base de données des fleurs
- `vercel.json` - Configuration Vercel

## API Endpoints

- `GET /api/messages` - Récupérer tous les messages
- `POST /api/messages` - Ajouter un message
- `GET /api/fleurs` - Récupérer toutes les fleurs
- `POST /api/fleurs` - Ajouter une fleur

