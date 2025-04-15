# 🏟️ Colina Smir – Système de Réservation des Terrains

Ce projet permet aux résidents de la résidence Colina Smir (Kabila Plage, Maroc) de réserver facilement les terrains de football et de tennis via une interface web responsive, connectée à Google Calendar.

---

## 📦 Structure du projet

```
colina-smir-reservation/
├── public/                  # Frontend (hébergé sur Netlify)
│   ├── index.html           # Formulaire de réservation responsive
│   └── logo.png             # Logo de la résidence
├── apps-script-backend/    # Backend Google Apps Script
│   └── Code.gs              # API GET /slots + POST /book avec CORS
└── README.md               # Ce fichier
```

---

## 🚀 Déploiement

### 1. 🔧 Backend Google Apps Script

- Ouvrir [Google Apps Script](https://script.google.com)
- Créer un nouveau projet
- Coller le contenu de `apps-script-backend/Code.gs`
- Déployer en tant qu’**Application Web** :
  - **Exécuter en tant que** : Moi
  - **Accès** : Tout le monde, même les anonymes
- Copier l'URL du type :
  ```
  https://script.google.com/macros/s/XXXXX/exec
  ```

---

### 2. 🌐 Frontend (Netlify)

- Aller sur [https://app.netlify.com/drop](https://app.netlify.com/drop)
- Glisser le dossier `public/` ou connecter ce repo GitHub
- Le site sera automatiquement accessible avec une URL Netlify (ex : `https://reservation-colinasmir.netlify.app`)

---

## 📱 Fonctionnalités

- 🔁 Sélection dynamique des créneaux disponibles par terrain et date
- 📅 Réservation confirmée via Google Calendar
- 📲 Interface responsive (mobile & desktop)
- 🌍 Multilingue (FR, AR, EN, ES) — basé sur la langue du navigateur

---

## 🎯 Améliorations possibles

- Ajout d’une page d’accueil ou bannière
- QR code imprimable pour accès rapide
- Intégration WhatsApp pour confirmations
- Stockage des réservations via Google Sheets (si besoin de reporting)

---

## 🛠 Développé par

> Projet initié par [@elmehdiattabou](https://github.com/elmehdiattabou) pour les besoins de gestion de la résidence Colina Smir – Ilot 7, été 2025.

---

📩 Pour toute suggestion : ouvrir une **issue** ou une **pull request** !
