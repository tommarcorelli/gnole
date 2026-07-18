# GNOLE. 🍹

**L'appli qui lance la soirée.** Une PWA de **14 jeux** à boire, 100 % web, un seul fichier (`index.html`) — vanilla JS, aucune dépendance.

👉 **Jouer :** https://tommarcorelli.github.io/gnole/

## Les 14 jeux

| | Jeu | Principe |
|---|---|---|
| 🃏 | **Picolo** | Le classique repensé — 8 modes, 200+ cartes, système de vies |
| 👑 | **Roi de la soirée** | King's cup : 52 cartes = 52 règles, un verre au centre |
| 🫵 | **Le plus susceptible** | On vote, un boulet est désigné, classement final |
| ⚡ | **Chrono Xtreme** | Défis minutés par intensité |
| 🎯 | **Action ou Vérité** | Tour par tour, intensité Soft / Épicé / Hot |
| 🧠 | **Culture Quiz** | Une question, on révèle : ceux qui se plantent boivent |
| 🎰 | **Roulette des gages** | La roue désigne un gage et une victime |
| 🤫 | **Paranoïa** | Question chuchotée, prénom lâché : révélée ou secrète ? |
| ⚔️ | **Duel** | Deux joueurs, un défi, un perdant qui boit |
| 🎲 | **Le Dé** | Un lancer, une règle |
| 🥃 | **Shot Roulette** | La roulette désigne qui descend son shot |
| ⏱️ | **Cadence infernale** | Un tempo sonore qui accélère : on boit à chaque bip |
| 🪜 | **Marathon** | De plus en plus à chaque manche, jusqu'à l'abandon |
| 🏓 | **Beer Pong** | Compteur de score (2 équipes, cups) |

## Fonctionnalités

- **Mode sans alcool** : remplace les gorgées par des points, dans tous les jeux
- **PWA installable** : s'ajoute à l'écran d'accueil, plein écran, fonctionne **hors-ligne**
- **Mobile-first**, dark glass sunset, animations et retours haptiques visuels

## Lancer en local

Ouvre simplement `index.html` dans un navigateur. Pour tester le mode hors-ligne (service worker), sers le dossier en HTTP :

```bash
python -m http.server 8000
# puis http://localhost:8000
```

---

*Jeux à consommer avec modération. Prévois de l'eau et ne force jamais quelqu'un qui ne veut pas boire.*
