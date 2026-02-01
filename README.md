# Portfolio de Johnny - Site Web Personnel 💼

## 📋 Description du Projet

Un site portfolio personnel développé en **HTML5, CSS3 et JavaScript vanilla**. Ce projet met en avant les compétences, projets et services d'un développeur web junior. Le site offre une expérience utilisateur moderne et réactive avec une navigation fluide et des animations élégantes.

**Auteur :** Johnny  
**Localisation :** Kinshasa, DRC  
**Email :** jonycokalondajk23@gmail.com

---

## 🎯 Fonctionnalités Principales

### 1. **Navigation Dynamique**

- Barre de navigation fixe avec design moderne
- Liens vers différentes sections (Home, About, Projects, Services, Contact)
- Style actif pour la section actuellement visible
- Design responsive et centré

### 2. **Section Home (Accueil)**

- Présentation professionnelle avec titre principal
- Description multilignes des compétences et motivations
- Badges de localisation et disponibilité
- Boutons d'appel à l'action :
  - "Hire Me" (Embauchez-moi)
  - "Download CV" (Télécharger le CV)
- Liens vers les réseaux sociaux (GitHub, Discord, LinkedIn, Instagram)

### 3. **Section About (À Propos)**

- Description détaillée du profil et passion pour le développement
- Présentation des valeurs (apprentissage continu, attention aux détails, design significatif)
- **Cards des Compétences :**
  - Languages : HTML, CSS, JavaScript
  - Education : Kadea Academy
  - Projects : Plus de 5 projets réalisés

### 4. **Section Projects (Projets)**

- **Affichage en Grille Responsive** (auto-fit avec minmax)
- **4 Projets Présentés :**
  1. **Portfolio Website**
     - Technologies : HTML, CSS, JavaScript
     - Description : Portfolio personnel
  2. **Twitter Clone**
     - Technologies : HTML, CSS, TailwindCSS, TypeScript, AdonisJS, AlpineJS
     - Description : Clone complet avec backend
  3. **Netflix Landing Page**
     - Technologies : HTML, CSS
     - Description : Page de destination avec animations et effets parallax
  4. **Task Manager**
     - Technologies : HTML, CSS, JavaScript
     - Description : Application CRUD avec interface épurée

- Chaque carte contient :
  - Titre du projet
  - Description
  - Tags de technologies
  - Boutons GitHub et Live Demo
  - Effets hover (élévation et ombre)

### 5. **Section Services**

- **3 Services Proposés :**
  1. **Web Application Development** - Applications scalables et modernes
  2. **Website Redesign & Improvement** - Modernisation et optimisation
  3. **Prototyping & MVP for Startups** - Prototypes pour validation d'idées

- **Design avec Effet Hover :**
  - Fond glissant avec transition de couleur
  - Texte qui change de couleur au survol
  - Animation fluide de 0.5s

### 6. **Section Contact**

- **Informations de Contact :**
  - Email : jonycokalondajk23@gmail.com
  - Téléphone : +243853134993
  - Localisation : DRC, Kinshasa

- **Formulaire de Contact :**
  - Champs : Nom, Email, Message
  - Intégration avec **Formspree** pour l'envoi d'emails
  - Validation HTML5
  - Design responsive

- **Liens Sociaux :**
  - GitHub, LinkedIn, WhatsApp
  - Survol avec changement de couleur (branding)

### 7. **Footer**

- Logo du portfolio
- Navigation interne (liens rapides)
- Liens sociaux
- Copyright 2025

---

## 🛠️ Technologies Utilisées

### **Frontend**

| Technologie              | Utilisation                  | Statut      |
| ------------------------ | ---------------------------- | ----------- |
| **HTML5**                | Structure sémantique du site | ✅ Actif    |
| **CSS3**                 | Styling et animations        | ✅ Actif    |
| **JavaScript (Vanilla)** | Interactivité et animations  | ⏸️ Commenté |
| **Font Awesome 7.0.1**   | Icônes (CDN)                 | ✅ Actif    |
| **Google Fonts**         | Polices typographiques       | ✅ Actif    |

### **Polices Typographiques (Google Fonts)**

- **Montserrat** (100-900) - Titres et navigation
- **Open Sans** (300-800) - Textes principaux
- **Playfair Display** (400-900) - Titres élégants
- **Unbounded** (200-900) - Éléments spéciaux

### **Services Externes**

- **Formspree** - Gestion des formulaires de contact
- **Font Awesome CDN** - Icônes vectorielles
- **Google Fonts API** - Polices personnalisées

### **Langages et Frameworks Mentionnés dans les Projets**

- TypeScript
- TailwindCSS
- AdonisJS (Framework Node.js)
- AlpineJS

---

## 📁 Structure des Fichiers

```
Mon portofolio/
├── index.html          # Structure HTML principale (287 lignes)
├── style.css           # Feuille de styles (776 lignes)
├── main.js             # Scripts JavaScript (172 lignes - partiellement commentés)
└── README.md           # Documentation (ce fichier)
```

---

## 📊 Analyse du Contenu

### **index.html (287 lignes)**

#### Structure Sémantique :

```
- <!DOCTYPE html> + Meta tags
- <header> : Barre de navigation
- <section class="home"> : Accueil
- <section class="about"> : À propos + compétences
- <section class="project"> : Galerie de projets
- <section class="services"> : Services proposés
- <section class="contact"> : Formulaire de contact
- <footer> : Pied de page
- <script src="main.js"> : Lien au JavaScript
```

#### Éléments Clés :

- Navigation avec 5 liens principaux
- Contenu multilingue (principalement anglais)
- Formulaire `action="https://formspree.io/f/xrelpkvr"` pour POST
- Intégration d'icônes Font Awesome partout
- Balises sémantiques (`<section>`, `<header>`, `<footer>`)
- Attributs `aria-label` pour l'accessibilité

---

### **style.css (776 lignes)**

#### Sections de Style :

1. **Reset et Variables** (Lignes 1-10)
   - `* { margin: 0; padding: 0; }` - Reset global

2. **Header/Navigation** (Lignes 11-47)
   - Position fixed, z-index: 1000
   - Flex layout centré
   - Effet de survol avec arrière-plan noir
   - Transitions fluides (0.3s)

3. **Section Home** (Lignes 48-183)
   - Layout flex avec écarts
   - Typo grande (70px) pour le titre
   - Boutons avec hover effects
   - Suivi de réseaux sociaux

4. **Section About** (Lignes 184-289)
   - Cards des compétences avec hover (translateY -6px, scale 1.03)
   - Bordure animée (#ff3333 au survol)
   - Ombre box-shadow au survol

5. **Section Projects** (Lignes 290-371)
   - Grid responsive : `grid-template-columns: repeat(auto-fit, minmax(280px, 1fr))`
   - Cards avec ombre et border-radius 16px
   - Tags de technologie avec fond bleu léger
   - Boutons avec icônes Font Awesome

6. **Section Services** (Lignes 372-433)
   - Grid responsive similaire
   - **Effet spécial hover :**
     - Pseudo-élément `::before` avec background glissant
     - `left: -100%` → `left: 0` en 0.5s
     - Couleur de texte qui change

7. **Section Contact** (Lignes 434-510)
   - Flex wrap responsive
   - Formulaire avec inputs et textarea
   - Focus avec `border-color: #474af0`
   - Bouton d'envoi avec background dégradé-like

8. **Footer** (Lignes 511-563)
   - Background noir
   - Layout flex centré
   - Liens avec hover color #474af0
   - Icônes sociales colorées au survol

9. **Animations** (Lignes 564-640)
   - `.reveal` : opacity 0, translateY(40px)
   - `.active-reveal` : fade in et slide up
   - `@keyframes fall` : animation de chute (0.9s)
   - Loading screen (commentée dans HTML)

10. **Responsive Design** (Lignes 641-776)
    - **Tablet (max-width: 1024px)** : Réduction des marges, direction colonne
    - **Mobile (max-width: 768px)** : Header caché, marges réduites, grille 1 colonne
    - **Petits écrans** : Boutons full-width, texte centré
    - Correction overflow-x hidden

---

### **main.js (172 lignes - Partiellement Commenté)**

#### Code Commenté (Fonctionnalités Proposées) :

1. **Navigation Active au Scroll** (Lignes 1-50)
   - Détection de la section actuellement visible
   - Synchronisation du menu actif avec scroll
   - Scroll smooth vers les sections

2. **Back to Top Button** (Lignes 53-87)
   - Bouton créé dynamiquement
   - Apparition après 500px de scroll
   - Animation de scale au survol
   - Retour au haut avec `window.scrollTo()`

3. **Scroll Reveal Animation** (Lignes 89-108)
   - Observer pour `.reveal` elements
   - Activation au scroll (150px avant l'élément)
   - Fade in + slide up

4. **Card Hover Effects** (Lignes 110-122)
   - Élévation du projet, service, etc.
   - `translateY(-8px) scale(1.05)`
   - Transition fluide

5. **Typing Effect** (Lignes 124-156)
   - Animation d'écriture/suppression de texte
   - Mots multiples : "Frontend Developer", etc.
   - Cursor animation

6. **Loading Screen** (Lignes 158-172)
   - Animation d'icônes au chargement
   - Disparition progressive (opacity fade)
   - Timeline d'animations décalées

---

## 🎨 Palette de Couleurs

| Couleur             | Code           | Utilisation                             |
| ------------------- | -------------- | --------------------------------------- |
| **Noir**            | `#000000`      | Navigation active, texte principal      |
| **Blanc**           | `#ffffff`      | Arrière-plan cards, texte sur fond noir |
| **Bleu Principal**  | `#1e40af`      | Titres, tags, boutons                   |
| **Bleu Accenté**    | `#474af0`      | Couleur thème (boutons, icons)          |
| **Bleu Clair**      | `#e0e7ff`      | Fond des tags technologie               |
| **Gris**            | `#555`, `#aaa` | Texte secondaire                        |
| **Rouge**           | `#ff3333`      | Bordure hover des cards                 |
| **Fond Card Hover** | `#fff5f5`      | Hover des compétences                   |

---

## 📱 Responsive Design

### **Breakpoints :**

1. **Desktop** (>1024px)
   - Marges : 160px 200px
   - Layouts en flex/grid
   - Tous les éléments visibles

2. **Tablet** (max-width: 1024px)
   - Marges : 120px 50px
   - Flexbox direction: column
   - Grille auto-fit 1fr

3. **Mobile** (max-width: 768px)
   - Header caché
   - Marges : 100px 20px
   - Tous les conteneurs en colonne
   - Grille 1 colonne uniquement
   - Boutons full-width

---

## 🚀 Déploiement et Utilisation

### **Installation Locale**

```bash
# 1. Cloner ou télécharger le projet
# 2. Ouvrir index.html dans un navigateur
# 3. Pas de build ou installation requise (HTML/CSS/JS pur)
```

### **Hébergement**

- Compatible avec GitHub Pages
- Compatible Netlify
- Compatible Vercel
- Fichiers statiques uniquement

### **Configuration Formspree**

Pour activer les formulaires de contact :

1. Se rendre sur [formspree.io](https://formspree.io)
2. Créer un compte
3. Remplacer l'URL du formulaire : `action="https://formspree.io/f/[VOTRE_ID]"`

---

## ✨ Fonctionnalités Avancées (Commentées)

Le code contient plusieurs fonctionnalités avancées actuellement **commentées** mais prêtes à être activées :

- ✅ Navigation synchronisée au scroll
- ✅ Bouton "back to top"
- ✅ Animations au défilement
- ✅ Effets hover avancés
- ✅ Effet de typing (machine à écrire)
- ✅ Loading screen personnalisé

**Pour activer :** Décommenter le code JavaScript dans `main.js`

---

## 🔗 Liens Importants

- **GitHub :** https://github.com/Saboo24
- **WhatsApp :** https://wa.me/243853134993
- **Email :** jonycokalondajk23@gmail.com
- **Formspree :** https://formspree.io/f/xrelpkvr

---

## 📈 Statistiques du Code

| Fichier    | Lignes   | Type           | Statut                 |
| ---------- | -------- | -------------- | ---------------------- |
| index.html | 287      | HTML           | ✅ Actif               |
| style.css  | 776      | CSS            | ✅ Actif               |
| main.js    | 172      | JavaScript     | ⏸️ Partiellement actif |
| **Total**  | **1235** | **Code Front** | **Production Ready**   |

---

## 🎓 Parcours et Formation

- **Formation :** Kadea Academy
- **Compétences :** HTML5, CSS3, JavaScript, TailwindCSS, TypeScript, AdonisJS, AlpineJS
- **Expérience :** 5+ projets réalisés
- **Statut :** Junior Developer - Disponible pour collaborations

---

## 📝 Améliorations Futures (Suggestions)

- [ ] Activer les animations scroll reveal
- [ ] Intégrer un système de blog
- [ ] Ajouter des filtres aux projets
- [ ] Implémenter un système de thème (dark/light mode)
- [ ] Ajouter des statistiques (compteurs)
- [ ] Intégrer une section "Témoignages"
- [ ] Optimiser les images (WebP, lazy loading)
- [ ] SEO avancé et meta tags
- [ ] Intégration d'analytiques (Google Analytics)

---

## 📄 Licence

Ce projet est le portfolio personnel de Johnny. Tous les droits sont réservés © 2025.

---

**Dernière mise à jour :** Février 2026  
**État :** Production Ready ✅
