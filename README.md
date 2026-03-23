# Mini-Compilateur PHP

[![JavaFX](https://img.shields.io/badge/JavaFX-21-blue)](https://openjfx.io/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

Un analyseur lexical et syntaxique pour PHP, développé en JavaFX. Cet outil permet d'analyser du code PHP, de générer la table des tokens, de détecter les erreurs lexicales et syntaxiques, et de fournir des statistiques sur le code. Il intègre également une interface web de présentation avec démonstration interactive.

---

## 📦 Fonctionnalités

- **Analyse lexicale** : découpe le code PHP en tokens (mots-clés, variables, chaînes, commentaires, etc.).
- **Analyse syntaxique** : vérifie la conformité de la grammaire PHP (basée sur un sous-ensemble).
- **Détection d'erreurs en temps réel** (dans l'application JavaFX).
- **Table des tokens** : affichage structuré avec ligne, type et valeur.
- **Gestion de projets** : arborescence des fichiers PHP d’un dossier.
- **Statistiques** : nombre de lignes, commentaires, fonctions, classes, tokens.
- **Documentation intégrée** : survol d’un mot‑clé pour afficher sa description.
- **Thème clair/sombre** personnalisable (dans l’application JavaFX).
- **Recherche de texte** dans l’éditeur (`Ctrl+F`).
- **Mode plein écran** (`F11`).
- **Paramètres de l’interface** : nombre de particules, vitesse de rotation des phrases, etc.
- **Site web de présentation** : démo interactive en ligne, explications, téléchargement.

---

## 🛠️ Technologies utilisées

| Composant | Technologie |
|-----------|-------------|
| **Application JavaFX** | Java 21, JavaFX 21, `TextArea` (éditeur simple) |
| **Site web** | HTML5, CSS3, JavaScript (animations particules, tokeniseur en ligne) |
| **Analyseur lexical** | Implémentation maison (expressions régulières) |
| **Analyseur syntaxique** | Analyseur descendant récursif (grammaire PHP simplifiée) |

---

## 🚀 Installation et exécution

### Prérequis

- **Java 21** ou supérieur (JavaFX 21 intégré)
- **Git** (optionnel, pour cloner le dépôt)

### Téléchargement

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/SAMOU2/php-compiler.git
   cd php-compiler
