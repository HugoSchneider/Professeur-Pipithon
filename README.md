# Pipithon - Système Intelligent d'Apprentissage Python 🚀

Bienvenue dans **Pipithon**, un projet novateur qui gamifie l'apprentissage du langage Python grâce à une intelligence adaptative, un système d'XP, des niveaux, et des défis progressifs !

## 🔍 Présentation du projet
**Pipithon** a été conçu pour transformer l'apprentissage du Python en une aventure ludique et motivante. Chaque joueur évolue à travers :

- des **cours interactifs**,
- des **QCM dynamiques** pour valider ses connaissances,
- des **défis de programmation adaptés** à son niveau,
- un **système de progression** inspiré du monde du gaming.

Grâce à une **IA adaptative**, le contenu proposé s'ajuste en fonction du profil et des performances de chaque joueur, garantissant ainsi un apprentissage sur-mesure et efficace.

## 🛠️ Fonctionnalités principales
- **Cours dynamiques** basés sur l'historique de progression
- **Défis Python** classés par niveau de difficulté
- **QCM intelligents** pour tester et consolider les acquis
- **IA adaptative** proposant automatiquement les meilleurs contenus
- **Système d'expérience (XP) et de niveaux** inspiré du gaming
- **Citadelle de citations** pour encourager et motiver 🌈
- **Suivi d'activité** et **exportation de statistiques personnalisées**
- **Historique détaillé** des activités pour analyser sa progression

## 📁 Architecture du projet
```bash
pipithon/
├── ai.py              # Module d'IA adaptative
├── bot.py             # Gestionnaire des commandes utilisateur
├── export.py          # Exportation et sauvegarde des données utilisateur
├── utils.py           # Fonctions utilitaires diverses
├── cours.json         # Contenus des cours interactifs
├── defis.json         # Liste des défis Python par niveau
├── citations.json     # Citations inspirantes
├── messages.json      # Messages systèmes et niveaux
├── levels.json        # Système d'XP et paliers de niveau
├── users.json         # Données utilisateurs
├── logs.json          # Historique des activités
├── xp_rules.json      # Règles d'attribution d'XP
└── README.md          # Documentation du projet (ce fichier)
```

## 🔧 Installation

### 1. Prérequis
- Python ≥ 3.8
- Bibliothèques nécessaires :
  - `discord`
  - `json`
  - `random`
  - `datetime`

Installez les dépendances avec :

```bash
pip install -r requirements.txt
```

### 2. Configuration
- Si utilisation via Discord : ajoutez votre `bot_token` dans votre environnement.

## 🚀 Lancement du projet
Exécutez le bot avec la commande suivante :

```bash
python bot.py
```

Utilisez ensuite les commandes interactives :

- `!start` — Démarrer votre aventure
- `!continuer` — Poursuivre votre progression
- `!stats` — Consulter vos statistiques

L'intelligence adaptative se charge de vous guider automatiquement à travers les cours, défis et QCM adaptés à votre profil.

## 💎 Système de Niveaux
| Niveau | XP nécessaire | Titre |
|:------:|:-------------:|:------|
| 1      | 0             | 🐣 Débutant de l'œuf |
| 5      | 100           | 🐍 Apprenti Python |
| 10     | 250           | 🔥 Initié des Boucles |
| 20     | 600           | 🧙‍♂️ Magicien du If |
| 30     | 1100          | 🤖 Maître des Fonctions |

> Plus de **90 niveaux** sont disponibles pour encourager la progression sur le long terme !

## 🎮 Exemple d'utilisation
```bash
!start
> Bienvenue, jeune aventurier du Python !

!continuer
> Aujourd'hui, ton défi : écrire une fonction qui affiche chaque lettre d'un mot...
```
Chaque action vous rapproche du prochain niveau et de nouveaux défis plus complexes !

## 📈 Améliorations futures
- Introduction d'un **mode tournoi multijoueurs**
- **Système de quêtes** quotidiennes et hebdomadaires
- Déverrouillage de **badges et récompenses spéciales**
- **Tableau de bord visuel** pour le suivi des progrès
- Ajout d'**animations** pour rendre l'expérience encore plus immersive

## 👨‍💻 Auteurs
Développé dans le cadre du cours **Techniques de Programmation II** par :

- Mehdi Fehri
- Zeller Emile
- Schneider Hugo

Merci d'avoir découvert **Pipithon**. Que l'aventure Pythonienne commence ! 🚀🐍
