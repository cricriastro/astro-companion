# 🔭 Astro Companion

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)
![Made with](https://img.shields.io/badge/made%20with-❤️-red)

**Ton compagnon intelligent de session astrophotographie**

[🚀 Voir l'application](https://cricriastro.github.io/astro-companion/) · [🐛 Signaler un bug](https://github.com/cricriastro/astro-companion/issues) · [💡 Suggérer une fonctionnalité](https://github.com/cricriastro/astro-companion/issues)

</div>

---

##  À propos

**Astro Companion** est une application web progressive (PWA) 100% gratuite conçue pour les astrophotographes amateurs et confirmés. Elle centralise toutes les informations essentielles avant et pendant une nuit de shooting : météo spécialisée, calcul d'autonomie, recommandations de cibles et réglages optimaux pour votre matériel.

> 🎯 **Objectif** : Remplacer 5 applications différentes par une seule interface intuitive, pensée par un astrophotographe, pour les astrophotographes.

---

## ✨ Fonctionnalités

### 🌙 Météo & Fenêtres de Tir
- **Score de la nuit** sur 100 (nuages + point de rosée + lune)
- **Phase lunaire** en temps réel avec impact sur le score
- **Fenêtres de tir** sur 2 nuits avec code couleur (Excellent / Moyen / Mauvais)
- **Prévisions heure par heure** scrollables avec température et point de rosée
- **Alerte buée intelligente** avec recommandation des cordons chauffants

### 🔧 Gestion du Setup
- **Base de données matériel** complète (montures, tubes, caméras, accessoires)
- **Calcul dynamique du poids** sur la monture avec indicateur visuel
- **Calcul d'autonomie** basé sur la consommation réelle du matériel
- **Sauvegarde locale** du setup (localStorage)

### 🎯 Cibles Recommandées
- **Sélection intelligente** selon la saison et les conditions
- **Filtres recommandés** par cible (Ha, OIII, SII, L, RGB)
- **Score de priorité** pour chaque cible

### ️ Réglages ASIAIR
- **Calibration automatique** selon la lunette et caméra de guidage
- **Agressivité RA/DEC** recommandée
- **Temps de pose guide** adapté au seeing
- **Gain caméra guide** optimal selon la magnitude de l'étoile

---

## 🛠️ Stack Technique

| Technologie | Utilisation |
|------------|-------------|
| **HTML5** | Structure sémantique |
| **CSS3** | Design responsive avec glassmorphism |
| **JavaScript (ES6+)** | Logique métier et calculs |
| **Open-Meteo API** | Données météo gratuites |
| **LocalStorage** | Persistance des données |
| **GitHub Pages** | Hébergement gratuit |

---

##  Installation & Utilisation

### Option 1 : Utiliser l'application en ligne
Rendez-vous directement sur : **[https://cricriastro.github.io/astro-companion/](https://cricriastro.github.io/astro-companion/)**

### Option 2 : Cloner le dépôt
```bash
git clone https://github.com/cricriastro/astro-companion.git
cd astro-companion
