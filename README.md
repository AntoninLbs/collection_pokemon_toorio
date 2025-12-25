# 🎴 Pokemon TCG Pocket - Collection Viewer

Interface web pour visualiser ta collection Pokemon TCG Pocket.

## 🚀 Déploiement

1. **Fork** ce repo ou crée un nouveau repo GitHub
2. Connecte le repo à **Vercel**
3. Déploie ! C'est tout 🎉

## 🔄 Mettre à jour ma collection

### Quand tu obtiens de nouvelles cartes :

1. Va sur [Pokemon Zone](https://pokemon-zone.com) et connecte ton compte Nintendo
2. Ouvre **DevTools** (F12) → onglet **Network** → filtre **Fetch/XHR**
3. Rafraîchis la page
4. Trouve la requête `mine/` (~30-40 kB)
5. Clic droit → **Copy response**
6. Remplace le contenu de `data/mine.json` dans GitHub
7. Vercel redéploie automatiquement ! ✅

### Quand une nouvelle extension sort :

1. Même procédure sur Pokemon Zone
2. Copie aussi la réponse de `card-data/` (~2 Mo)
3. Remplace `data/card-data.json`
4. + Remplace `data/mine.json`
5. Commit & push → Vercel redéploie

## 📁 Structure

```
pokemon-collection/
├── index.html          # Interface web
├── data/
│   ├── mine.json       # Ta collection (à mettre à jour)
│   └── card-data.json  # Base de données des cartes
└── README.md
```

## ✨ Fonctionnalités

- 📊 Progression par extension
- 🔍 Recherche et filtres (rareté, type, extensions)
- ✅ Cartes possédées / ❌ Manquantes / 🔄 Doublons
- 🖼️ Cartes manquantes en noir & blanc
- 📱 Responsive (mobile friendly)

## 🎮 Joueur

- **Nom** : Toorio
- **Niveau** : 51

---

Made with ❤️ pour la communauté Pokemon TCG Pocket
