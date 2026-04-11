# 🚗 CarbuLoc

**Carte interactive des prix des carburants en France**

Une application web pour trouver les stations-service les moins chères autour de vous.

## ✨ Fonctionnalités

- 🗺️ **Carte interactive** avec thème sombre/clair
- 🔍 **Recherche** par ville ou code postal (autocomplétion Photon)
- 📍 **Géolocalisation** pour trouver les stations proches
- ⛽ **5 carburants** : Gazole, SP95, SP98, E10, E85
- 📊 **Classement** des stations par prix
- 🏷️ **Logos des enseignes** (Total, Leclerc, Carrefour, etc.)
- ⚠️ **Ruptures de stock** signalées
- 📱 **Responsive** : fonctionne sur mobile et desktop

## 🚀 Démo

👉 [Ouvrir CarbuLoc](https://carbuloc.github.io/CarbuLoc/)

## 📦 Installation locale

```bash
# Cloner le repo
git clone https://github.com/Carbuloc/CarbuLoc.git
cd CarbuLoc

# Lancer un serveur local (Python 3)
python -m http.server 8080

# Ouvrir dans le navigateur
# http://localhost:8080
```

## 🛠️ Technologies

- **HTML/CSS/JS** vanilla (pas de framework)
- **Leaflet.js** pour la cartographie
- **API data.economie.gouv.fr** pour les prix
- **API prix-carburants.2aaz.fr** pour les noms de stations
- **Photon API** pour l'autocomplétion

## 📄 Licence

MIT License - Libre d'utilisation

## 🙏 Crédits

- Données : [Prix des carburants - data.gouv.fr](https://www.data.gouv.fr/fr/datasets/prix-des-carburants-en-france-flux-instantane-v2/)
- Cartographie : [Leaflet](https://leafletjs.com/) + [CartoDB](https://carto.com/)
- Logos : [prix-carburants.2aaz.fr](https://www.prix-carburants.2aaz.fr/)
