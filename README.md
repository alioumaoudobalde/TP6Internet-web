
---

## 🧾 **README.md – TP6 Animations (HTML, CSS, jQuery)**

> **Licence Informatique – 1ère année (UPJV)**  
> Objectif : apprendre à créer des animations web simples et dynamiques à l’aide du **DOM**, du **CSS** et de **jQuery**.

---

## 🧠 Objectifs pédagogiques
- Manipuler le **DOM** avec jQuery.  
- Créer des **animations visuelles** (apparition, disparition, transformations).  
- Comprendre la différence entre **modification du DOM** et **modification des styles**.  
- Utiliser les **sélecteurs jQuery** et les **événements** (`click`, `hover`...).  
- Combiner **CSS** et **JavaScript** pour des interfaces interactives.

---

## 📁 Structure du TP

```
TP6/
├── question1.html
├── question2.html
├── question3.html
├── question4.html
├── question5.html
├── images/
│   ├── js.jpeg
│   ├── js1.jpeg
│   ├── js2.jpeg
│   ├── roi.jpg
│   ├── dame.jpg
|   ├── desin.jpg
│   ├── valet.jpg
│   ├── 10.jpg
│   ├── as.jpg
│   └── autres images nécessaires


````

---

## ⚙️ Instructions Linux de départ

Avant de commencer, crée ton dossier de travail :

```bash
cd ~
mkdir -p public_html/TP6
cd public_html/TP6
````

Ajoute ensuite les fichiers `.html` et le dossier `images/`.

---

## 💡 Résumé des questions

### 🧩 **Question 1 – fadeOut() d’une image**

Créer une page avec un texte “cliquez-moi” et une image.
Au clic, l’image disparaît progressivement grâce à `animate()` (ou `fadeOut()`).

👉 *Objectif : comprendre comment jQuery agit sur le DOM sans le modifier structurellement.*

---

### 🖼️ **Question 2 – Deux images et texte à afficher/masquer**

Deux images côte à côte + un paragraphe.

* Survol = bordure bleue.
* Clic sur l’image de gauche = `fadeIn()`.
* Clic sur l’image de droite = `fadeOut()`.

---

### 🔘 **Question 3 – Boutons interactifs**

Trois boutons (styles différents) + un bouton **Clear**.
Chaque bouton affiche son contenu (texte + image).
**Seul le 2e** bouton déclenche l’apparition.

👉 *Apprentissage : gestion des événements, toggle d’éléments, interactions simples.*

---

### ♠️ **Question 4 – Jeu de cartes**

Afficher une main : **Roi, Dame, Valet, 10**.

* Ordre d’affichage assuré par `z-index`.
* Survol du Roi → devient **As** (en CSS pur).
* Survol du 10 → devient **As** (avec jQuery).
* Aucune autre image dans le `body`.

👉 *Mélange CSS/jQuery et logique d’empilement (z-index).*

---

### 🍽️ **Question 5 – Menu déroulant CSS**

Créer une liste à deux niveaux (“Entrées”, “Plats”).
Au survol, le sous-menu s’affiche (sans JS).

👉 *Objectif : exploiter les propriétés d’affichage CSS (`display`, `position`, `hover`).*

---

## 🧰 Technologies utilisées

* **HTML5**
* **CSS3 (animations, hover, z-index)**
* **jQuery 3.6.0**

Lien CDN jQuery utilisé :

```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
```

---

## 🧑‍💻 Auteur

**[BALDE ALIOU MAOUDO]**
Université de Picardie Jules Verne – 2023–2024
Cours : *Internet & Web – Animations (TP6)*

---

## 🧾 Licence

Projet pédagogique libre – vous pouvez le partager, modifier et réutiliser pour vos propres apprentissages.
Merci de mentionner la source si vous le diffusez. 😉

---

## 📸 Aperçu

![aperçu des animations](images/main.jpg)
*(Exemple : question 4 – main de cartes)*

---

## 🌐 Validation

Avant de rendre le TP :

* Passez vos pages au **validator W3C** :
  [https://validator.w3.org/](https://validator.w3.org/)
* Testez les animations sur **serveurstleu** ou un **serveur local**.

---

**Bon code et amusez-vous avec les animations ✨**

```

---

