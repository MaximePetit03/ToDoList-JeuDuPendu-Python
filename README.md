# 🐍 Python GUI Bundle: ToDo & Hangman

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![UI Library](https://img.shields.io/badge/UI-CustomTkinter-orange)](https://github.com/TomSchimansky/CustomTkinter)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 📸 Aperçu

| ToDo List Manager | Jeu du Pendu |
| :---: | :---: |
| ![Aperçu ToDo](<img width="847" height="774" alt="Image" src="https://github.com/user-attachments/assets/48cf3518-01de-46bd-81ff-c92b8425e209" />) | ![Aperçu Pendu](<img width="865" height="781" alt="Image" src="https://github.com/user-attachments/assets/3135299a-d565-4bef-a99e-bc752449820e" />) |

---

## 📋 1. ToDo List Manager
Un gestionnaire de tâches robuste axé sur l'efficacité et la persistance.

* **Persistance locale** : Sauvegarde automatique de vos tâches dans `list.txt`.
* **Édition intuitive** : Double-cliquez sur une tâche pour la modifier instantanément.
* **Gestion groupée** : Support de la multi-sélection pour supprimer plusieurs objectifs d'un coup.
* **Raccourcis Clavier** :
    * `Entrée` : Ajouter/Confirmer.
    * `Ctrl + A` : Tout sélectionner.
    * `Suppr` : Supprimer la sélection.

---

## 🎮 2. Jeu du Pendu
Le grand classique revisité avec une interface dynamique.

* **Moteur Graphique** : Dessin vectoriel du pendu évolutif sur un `Canvas` dédié.
* **Lexique Riche** : Plus de 150 mots classés (Sciences, Animaux, Verbes, etc.).
* **Logique de Jeu** : Gestion automatique des essais (11 max), détection des doublons et reset temporisé après victoire ou défaite.
* **Sécurité** : Filtrage intelligent des entrées (lettres uniquement).

---

## ⚙️ Installation

### Prérequis
Assurez-vous d'avoir Python installé.

### Dépendances
Installez la bibliothèque d'interface moderne :

```pip install customtkinter```

# 🚀 Lancement

**Pour tester les applications, clonez le repo et lancez les scripts :**

Pour la ToDo List :

```python main_todo.py```

Pour le Jeu du Pendu :

```python interfacePendu.py```

🛠️ Stack Technique

**Langage : Python 3**

**GUI Library : CustomTkinter**
