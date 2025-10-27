# 🍽️ Ohmyfood

Projet Front-End réalisé dans le cadre de la formation OpenClassrooms.  
L'objectif est de développer un site mobile-first pour une startup fictive de réservation de menus gastronomiques.

---

## 🚀 Fonctionnalités

- Affichage des menus de 4 restaurants
- Animations CSS pour les transitions et chargements
- Responsive design (mobile-first)
- Structure Sass modulaire

---

## 🛠️ Technologies utilisées

- HTML5
- Sass (SCSS)
- CSS3
- VS Code + Live Sass Compiler

---

## 🔧 Compilation Sass

Ce projet utilise **Live Sass Compiler** pour générer les fichiers `.css` à partir du fichier principal `main.scss`.

### 📦 Installation recommandée

- Extension VS Code : [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass)

### 📁 Structure Sass

assets/styles/scss/ 
    ├── abstracts/ # Variables, mixins, fonctions 
    ├── base/ # Reset, base typographique 
    ├── components/ # Boutons, cartes, etc. 
    ├── layouts/ # Header, footer, container 
    ├── pages/ # Styles spécifiques aux pages 
    ├── utils/ # Animations, helpers 
    └── main.scss # Fichier principal

### ⚙️ Configuration Live Sass Compiler

Les fichiers compilés sont ignorés dans le dépôt (`.gitignore`) et générés automatiquement :

- `main.css` → version lisible
- `main.min.css` → version minifiée
- `.map` → pour le débogage dans DevTools

---

## 📄 À propos

Ce projet est réalisé dans un but pédagogique.  
Design fourni par OpenClassrooms.

---

## 📬 Contact

Développé par Mihai  
📍 Paris, France  
