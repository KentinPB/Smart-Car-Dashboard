# 📚 Smart Car Dashboard Documentation

> Documentation technique officielle du projet **Smart Car Dashboard**.

<p align="center">

![Documentation](https://img.shields.io/badge/Documentation-En%20cours-blue?style=for-the-badge)
![Architecture](https://img.shields.io/badge/Architecture-Modulaire-success?style=for-the-badge)
![Hardware](https://img.shields.io/badge/Hardware-Embedded%20System-C51A4A?style=for-the-badge)
![CAN Bus](https://img.shields.io/badge/CAN%20Bus-Mazda%20MX--5%20ND-blue?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-Français-blueviolet?style=for-the-badge)

</p>

---

# 👋 Bienvenue

Cette documentation rassemble l'ensemble des informations techniques nécessaires à la compréhension, au développement et à l'évolution du projet **Smart Car Dashboard**.

Vous y trouverez notamment :

- 🏗️ l'architecture du système
- 🔌 la conception électronique
- 💻 l'architecture logicielle
- 📡 le fonctionnement du réseau CAN
- 📦 la liste complète des composants
- 🔧 les schémas de câblage

---

# 🧭 Où commencer ?

Selon ce que vous recherchez...

## 👀 Je découvre le projet

➡️ Commencez par :

- 📐 [Architecture générale](architecture.md)
- 🔌 [Architecture matérielle](hardware.md)
- 💻 [Architecture logicielle](software.md)

---

## 🔌 Je souhaite reproduire le montage

➡️ Consultez :

- 📦 [Bill of Materials](bom.md)
- 🔧 [Schémas de câblage](wiring.md)
- 🔌 [Documentation Hardware](hardware.md)

---

## 📡 Je veux comprendre le CAN Bus

➡️ Consultez :

- 📡 [CAN Bus](can-bus.md)
- 💻 [Architecture logicielle](software.md)

---

## 👨‍💻 Je souhaite contribuer

➡️ Nous recommandons de lire :

1. 📐 Architecture
2. 💻 Software
3. 🔌 Hardware

---

# 📚 Documentation

## 🏗️ Architecture

> Comprendre l'organisation globale du projet.

| Document | Description |
|-----------|-------------|
| 📐 [architecture.md](architecture.md) | Vue d'ensemble du système |
| 💻 [software.md](software.md) | Applications exécutées sur le Raspberry Pi |
| 🔌 [hardware.md](hardware.md) | Électronique et conception matérielle |

---

## 🚗 Véhicule

> Documentation liée à la Mazda MX-5 ND.

| Document | Description |
|-----------|-------------|
| 📡 [can-bus.md](can-bus.md) | Réseau CAN et décodage |
| 🔧 [wiring.md](wiring.md) | Câblage et intégration |

---

## 📦 Conception

> Liste des composants utilisés.

| Document | Description |
|-----------|-------------|
| 📦 [bom.md](bom.md) | Bill of Materials |

---

# 📁 Organisation de la documentation

```text
docs/
│
├── README.md          ← Vous êtes ici
├── architecture.md
├── bom.md
├── can-bus.md
├── hardware.md
├── software.md
└── wiring.md
```

---

# 🚀 Documentation à venir

Au fil de l'avancement du projet, cette documentation sera enrichie avec :

- 📷 Photos du montage
- 📐 Schémas électroniques
- 🔋 Gestion énergétique
- ⚡ Séquence de démarrage
- 📊 Diagrammes Mermaid
- 🧪 Procédures de tests
- 🛠️ Guides d'installation
- 📈 Décodage des trames CAN

---

# 💡 Philosophie du projet

Le but n'est pas uniquement de réaliser un tableau de bord embarqué.

Ce dépôt a également vocation à servir de support d'apprentissage autour :

- du développement logiciel ;
- des systèmes embarqués ;
- de Linux ;
- de l'électronique ;
- du bus CAN ;
- de l'architecture logicielle.

L'ensemble de la documentation est donc rédigé de manière à être compréhensible, maintenable et évolutive.

---

<div align="center">

### 📖 *Une bonne documentation est aussi importante qu'un bon code.*

Retour au **[README principal](../README.md)**

</div>