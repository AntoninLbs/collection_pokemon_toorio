# 🎴 Pokemon TCG Pocket - Collection Toorio

Interface web pour visualiser ta collection Pokemon TCG Pocket.

## 🚀 Déploiement

1. **Fork** ce repo ou crée un nouveau repo GitHub
2. Connecte le repo à **Vercel**
3. Deploy ! C'est tout 🎉

## 🔄 Mettre à jour ma collection

Pour mettre à jour ta collection (nouvelles cartes ou nouvelle extension) :

1. Va sur [Pokemon Zone](https://pokemon-zone.com) et connecte ton compte Nintendo
2. Ouvre **DevTools** (F12) → onglet **Network** → filtre **Fetch/XHR**
3. Rafraîchis la page
4. Trouve la requête `mine/` (~30-40 kB)
5. Clic droit → **Copy response**
6. **Envoie-moi le fichier** et je te génère le nouveau `card-data.json`
7. Remplace `data/card-data.json` dans GitHub
8. Vercel redéploie automatiquement ! ✅

## 📁 Structure

```
pokemon-collection/
├── index.html          # Interface web
├── data/
│   └── card-data.json  # Données de collection (à mettre à jour)
└── README.md
```

## ✨ Fonctionnalités

- 📊 Progression par extension
- 🔍 Recherche et filtres (rareté, type, extensions multiples)
- ✅ Cartes possédées / ❌ Manquantes / 🔄 Doublons
- 🖼️ Cartes manquantes en noir & blanc
- 📱 Responsive (mobile friendly)

## 🎮 Joueur

- **Nom** : Toorio
- **Niveau** : 51

---

Made with ❤️ pour Pokemon TCG Pocket
