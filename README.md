# 🔌 Smart Car Dashboard – Mazda MX-5 ND

> 🚧 Un système embarqué open source permettant de collecter, traiter et visualiser les données du bus CAN d'une **Mazda MX-5 ND** grâce à un **ESP32** et un **Raspberry Pi 5**.

<p align="center">

![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-En%20développement-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%205-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-WROOM-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![CAN Bus](https://img.shields.io/badge/CAN%20Bus-Automotive-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-17-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Debian-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</p>

---

# 📑 Sommaire

- 📖 Présentation
- ✨ Fonctionnalités
- 🎯 Objectifs
- 📂 Structure du dépôt
- 📚 Documentation
- 🛣️ Roadmap
- ⚠️ Avertissement
- 📜 Licence
- 🤝 Contributions

---

# 📖 Présentation

**Smart Car Dashboard** est un projet personnel ayant pour objectif de concevoir un système embarqué modulaire capable de collecter, traiter et afficher les données du **bus CAN** d'une **Mazda MX-5 ND**.

Le projet combine électronique embarquée, développement logiciel et interface Web afin de créer un tableau de bord moderne, évolutif et entièrement personnalisable.

L'architecture repose principalement sur :

- 🔌 **ESP32** pour la gestion de l'alimentation et le contrôle embarqué
- 🍓 **Raspberry Pi 5** pour l'acquisition, le traitement et l'affichage des données
- 📡 **Bus CAN** pour la communication avec le véhicule

Au-delà du résultat final, ce projet est également un support d'apprentissage autour de :

- 🚗 l'ingénierie automobile
- 📡 la communication CAN Bus
- 🔌 l'IoT
- ⚡ l'électronique embarquée
- 🐧 Linux
- 💻 l'architecture logicielle
- 🌐 le développement Web

---

# ✨ Fonctionnalités

## ✅ Disponibles

- 📚 Documentation complète du projet
- 📦 Bill of Materials (BOM)
- 🧩 Architecture matérielle et logicielle
- 📖 Documentation du réseau CAN

## 🚧 En développement

- 📡 Lecture des réseaux HS-CAN et MS-CAN
- ⚡ Gestion intelligente de l'alimentation
- 🔋 Surveillance de la batterie
- 📊 Dashboard temps réel
- 🌐 Interface Web
- 💾 Journalisation des données
- 📈 Visualisation des informations du véhicule

---

# 🎯 Objectifs

- Construire une plateforme embarquée fiable et évolutive
- Lire et décoder les différents réseaux CAN du véhicule
- Développer une interface utilisateur moderne
- Concevoir une architecture facilement maintenable
- Approfondir mes compétences en électronique, Linux, IoT et développement logiciel
- Documenter entièrement le projet afin qu'il puisse être compris et reproduit

---

# 📂 Structure du dépôt

```text
smart-car-dashboard/
│
├── .github/          # GitHub Actions
├── assets/           # Images et ressources
├── docs/             # Documentation technique
├── firmware/         # Firmware ESP32
├── hardware/         # Conception électronique
├── software/         # Applications Raspberry Pi
├── scripts/          # Scripts d'installation
├── tests/            # Tests
│
├── LICENSE
├── README.md
└── .gitignore
```

La structure détaillée du projet ainsi que le rôle de chaque dossier sont disponibles dans la documentation.

---

# 📚 Documentation

Toute la documentation est disponible dans le dossier [docs/](docs/)

| Document | Description |
|----------|-------------|
| 📖 [README.md](docs/README.md) | Sommaire de la documentation |
| 📐 [architecture.md](docs/architecture.md) | Architecture matérielle et logicielle |
| 📦 [bom.md](docs/bom.md) | Bill of Materials (liste des composants) |
| 🔌 [hardware.md](docs/hardware.md) | Documentation électronique |
| 💻 [software.md](docs/software.md) | Architecture logicielle |
| 📡 [can-bus.md](docs/can-bus.md) | Documentation du réseau CAN |
| 🔧 [wiring.md](docs/wiring.md) | Plans de câblage |

---

# 🛣️ Roadmap

## 📚 Documentation

- [x] Architecture générale
- [x] Choix des composants
- [x] Documentation initiale
- [x] Organisation du dépôt GitHub

## 🔌 Firmware ESP32

- [ ] Gestion de l'alimentation
- [ ] Gestion Wake / Sleep
- [ ] Surveillance de la batterie
- [ ] Communication avec le Raspberry Pi

## 📡 CAN Bus

- [ ] Lecture HS-CAN
- [ ] Lecture MS-CAN
- [ ] Décodage des trames
- [ ] Base de données des identifiants CAN

## 💻 Logiciel

- [ ] Traitement des données
- [ ] API
- [ ] Dashboard Web
- [ ] Journalisation
- [ ] Interface d'administration

## 🚀 Améliorations futures

- [ ] Historique des trajets
- [ ] Export CSV
- [ ] Graphiques avancés
- [ ] Statistiques
- [ ] Interface mobile
- [ ] Mises à jour OTA de l'ESP32

---

# ⚠️ Avertissement

> [!WARNING]
> Ce projet interagit directement avec le réseau électronique d'un véhicule.
>
> Toute modification du système électrique d'un véhicule comporte des risques pouvant entraîner :
>
> - une décharge de la batterie ;
> - un dysfonctionnement électronique ;
> - des dommages matériels ;
> - une perte de garantie constructeur ;
> - voire un risque pour la sécurité des occupants.
>
> **L'utilisation des schémas, du matériel, des conseils et du code source de ce dépôt se fait entièrement sous votre propre responsabilité.**

L'auteur ne pourra être tenu responsable des dommages matériels, logiciels, financiers ou corporels résultant de l'utilisation ou de la reproduction de ce projet.

Avant toute installation :

- Vérifiez soigneusement votre câblage.
- Utilisez des protections électriques adaptées.
- Respectez les règles de sécurité.
- N'intervenez jamais sur un véhicule en circulation.

---

# 📜 Licence

Ce projet est distribué sous licence **MIT**.

---

# 🤝 Contributions

Les suggestions, corrections, retours d'expérience et améliorations sont les bienvenus.

N'hésitez pas à ouvrir une **Issue** ou une **Pull Request**.

---

# 👨‍💻 Auteur

**Kentin**

Développeur Web & Web Mobile

Passionné par le développement logiciel, les systèmes embarqués, l'IoT et l'ingénierie automobile.

---

<p align="center">

### 🚗 *"Transformer les données d'un véhicule en informations exploitables, une trame CAN à la fois."*

⭐ Si ce projet vous intéresse, n'hésitez pas à laisser une étoile au dépôt !

</p>
