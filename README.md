# Dashboard UI - Projet de tableau de bord moderne

Un tableau de bord moderne et responsive construit avec HTML et CSS pur, sans dépendances JavaScript supplémentaires (à l'exception de Font Awesome pour les icônes).

![Dashboard Preview](preview.png)

##�� Table des matières

- [Fonctionnalités](#fonctionnalités)
- [Technologies utilisées](#technologies-utilisées)
- [Structure du projet](#structure-du-projet)
- [Guide d'installation](#guide-dinstallation)
- [Architecture CSS](#architecture-css)
- [Responsive Design](#responsive-design)
- [Bonnes pratiques](#bonnes-pratiques)

## ✨ Fonctionnalités

- Design moderne et épuré
- Interface entièrement responsive
- Sidebar de navigation
- Statistiques en temps réel
- Tableau des projets actifs
- Système de badges pour les priorités
- Barres de progression
- Mode mobile avec menu hamburger
- Animations et transitions fluides

## 🛠 Technologies utilisées

- HTML5
- CSS3 (Variables CSS, Flexbox, Grid)
- JavaScript (minimal, pour la navigation mobile)
- Font Awesome (icônes)
- Google Fonts (Police Inter)

## 📁 Structure du projet 


## 🚀 Guide d'installation

1. Clonez le repository

bash
git clone https://github.com/votre-username/dashboard-ui.git


2. Assurez-vous d'avoir les images nécessaires :
   - Logos des projets (dropbox-logo.png, slack-logo.png, etc.)
   - Images d'avatar (avatar1.jpg, avatar2.jpg, avatar3.jpg)

3. Ouvrez `index.html` dans votre navigateur

## 🎨 Architecture CSS

### Variables CSS


css
:root {
--primary-color: #6366f1;
--primary-hover: #4f46e5;
--sidebar-bg: #1e293b;
--body-bg: #f8fafc;
/ ... autres variables ... /
}


### Composants principaux

1. **Sidebar**
   - Position fixe
   - Dégradé de couleur en arrière-plan
   - Navigation avec icônes
   - Animation de survol

2. **Header**
   - Barre de recherche
   - Bouton de profil
   - Position sticky pour une meilleure UX

3. **Stats Cards**
   - Grid layout 4 colonnes
   - Animations au survol
   - Icônes avec fond coloré

4. **Projects Table**
   - Design moderne avec espacement optimal
   - Badges de priorité colorés
   - Barres de progression
   - Groupes d'avatars avec superposition

## 📱 Responsive Design

### Breakpoints
- Desktop: > 1024px
- Tablet: 768px - 1024px
- Mobile: < 768px
- Small Mobile: < 480px

### Adaptations mobiles
1. **Sidebar**
   - Se transforme en menu hamburger
   - Animation de glissement
   - Fermeture au clic extérieur

2. **Stats Cards**
   - Passage de 4 à 2 colonnes sur tablette
   - 1 colonne sur mobile

3. **Table**
   - Scrollable horizontalement
   - Largeur minimum maintenue

## ⚡ Bonnes pratiques

1. **Performance**
   - Utilisation de CSS moderne (Grid, Flexbox)
   - Transitions optimisées
   - Minimum de JavaScript

2. **Maintenabilité**
   - Variables CSS pour les couleurs et ombres
   - Structure CSS organisée par composants
   - Nommage explicite des classes

3. **Accessibilité**
   - Contraste de couleurs optimal
   - Structure HTML sémantique
   - Navigation au clavier possible

## 🎯 Étapes de construction

1. **Mise en place de la structure**
   - Configuration HTML de base
   - Importation des polices et icônes
   - Définition des variables CSS

2. **Construction du layout**
   - Sidebar
   - Header
   - Conteneur principal

3. **Développement des composants**
   - Stats cards
   - Tableau des projets
   - Badges et barres de progression

4. **Responsive Design**
   - Media queries
   - Adaptations mobiles
   - Menu hamburger

5. **Finitions**
   - Animations
   - Transitions
   - Optimisations

## 🔄 Mises à jour futures possibles

- [ ] Mode sombre
- [ ] Plus de visualisations de données
- [ ] Filtres de projets
- [ ] Système de notifications
- [ ] Personnalisation des thèmes

## 📝 Notes

- Les images doivent être optimisées pour le web
- Les polices sont chargées via Google Fonts
- Le site est testé sur les navigateurs modernes


