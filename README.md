# Projet BOOKI - Intégration et mise en œuvre en HTML & CSS

## Description

Le projet **BOOKI** est un site web fictif destiné à aider les utilisateurs à trouver des hébergements et des activités touristiques. Ce projet constitue le **Projet 02** de la formation **Développeur web** d'OpenClassrooms et vise à intégrer des maquettes fournies (desktop, tablette, mobile) en utilisant **HTML5** et **CSS3**.

L'objectif de cette intégration est de développer un site web responsive, conforme aux standards du W3C et aux meilleures pratiques de développement, tout en respectant les spécifications fonctionnelles définies dans la **note de synthèse** fournie par l'équipe produit.

**Lien vers les maquettes** : [Maquettes Booki sur Figma](https://www.figma.com/design/r9YJyUkpVdrxzBBKGH7reY/Maquettes-Booki-(desktop%2C-mobile%2C-tablette)?node-id=3-0&t=EDpqUDPc1Zh4s3jV-1)

## Structure du projet

Le projet est structuré autour des éléments suivants :

- **`index.html`** : Contient la structure HTML sémantique du site, incluant des sections principales telles que le formulaire de recherche, les cartes d’hébergements et les activités touristiques.
- **`css/style.css`** : Fichier contenant les styles CSS pour mettre en page le site, avec l'utilisation de `flexbox`, `grid` et des media queries pour garantir une expérience responsive.
- **`images/`** : Ce dossier contient toutes les images nécessaires à l'interface (hébergements, activités, logo, etc.).

## Fonctionnalités implémentées

Les fonctionnalités suivantes ont été intégrées conformément aux spécifications fonctionnelles et aux maquettes fournies :

1. **Fonction de recherche** : Un champ de recherche éditable permet à l’utilisateur de saisir une ville pour trouver des hébergements. Ce champ est inclus dans un formulaire, bien que la recherche ne soit pas encore fonctionnelle dans cette version. La connexion à une base de données ou l'affichage dynamique des résultats sera implémenté dans une version future.

2. **Liens de navigation “Hébergements” et “Activités”** : Les liens situés dans l'en-tête permettent de naviguer vers les sections "Hébergements à Marseille" et "Activités à Marseille".

3. **Cartes cliquables** : Les cartes d’hébergements et d’activités sont entièrement cliquables, et des liens `href="#"` sont utilisés pour simuler la navigation dans cette version.

4. **Filtres de recherche** : Les filtres de recherche permettent de sélectionner des thématiques d’hébergement (économie, familial, romantique, Nos pépites), avec un effet de survol (hover) qui change la couleur des filtres. Ces filtres ne sont pas encore fonctionnels.

5. **Design responsive** : Le site est entièrement responsive et s'adapte aux écrans desktop, tablette et mobile.

6. **Améliorations de l'accessibilité** : Des descriptions alternatives (`alt`) ont été ajoutées aux images, et des labels explicites sont présents dans les formulaires pour garantir l'accessibilité.

## Roadmap

La roadmap ci-dessous détaille les étapes déjà réalisées ainsi que les fonctionnalités à venir dans les prochaines versions du projet :

### 1. Intégration des maquettes

- [x] **Intégration des maquettes desktop, tablette et mobile** : Toutes les maquettes ont été correctement intégrées en respectant les designs pour chaque type d’appareil.
- [x] **Structure HTML conforme** : Utilisation des balises sémantiques telles que `<header>`, `<nav>`, `<main>`, `<section>` et `<footer>` pour une organisation claire et optimisée pour le SEO.

### 2. Fonctionnalités de navigation

- [x] **Liens de navigation fonctionnels** : Les liens de navigation “Hébergements” et “Activités” dans l'en-tête mènent correctement aux sections correspondantes sur la page.

### 3. Recherche d'hébergements

- [x] **Formulaire de recherche intégré** : Le formulaire de recherche est fonctionnel au niveau de l'interface (champ de saisie éditable), mais non connecté à une base de données.
- [ ] **Implémentation de la recherche fonctionnelle** : À implémenter dans une version future pour permettre la recherche d’hébergements en fonction de la ville saisie.

### 4. Cartes des hébergements et activités

- [x] **Cartes cliquables** : Les cartes d’hébergements et d’activités sont entièrement cliquables et respectent l'interface des maquettes (utilisation de `href="#"` pour simuler les liens).
- [ ] **Liens fonctionnels des cartes** : À implémenter pour connecter chaque carte à des pages spécifiques d’hébergement ou d’activité.

### 5. Filtres de recherche

- [x] **Filtres interactifs** : Les filtres de recherche (économie, familial, romantique, Nos pépites) changent de couleur au survol, respectant les spécifications de l’interface.
- [ ] **Filtres fonctionnels** : À implémenter pour filtrer les hébergements en fonction des critères sélectionnés par les utilisateurs.

### 6. Responsive design

- [x] **Design responsive complet** : Le site s'adapte correctement aux tailles d’écrans desktop, tablette et mobile en utilisant `flexbox`, `grid` et des media queries.

### 7. Accessibilité et SEO

- [x] **Descriptions alternatives** : Des descriptions `alt` ont été ajoutées à toutes les images pour améliorer l’accessibilité.
- [x] **Labels explicites pour les formulaires** : Chaque champ de formulaire est associé à des labels explicites pour garantir l'accessibilité.

### 8. Validation W3C

- [x] **Validation W3C** : Le code HTML et CSS a été validé pour être conforme aux standards du W3C.

## Technologies utilisées

- **HTML5** : Structuration des pages avec des balises sémantiques.
- **CSS3** : Gestion de la mise en page avec `flexbox` et `grid`, utilisation de media queries pour un affichage responsive.
- **Font Awesome** : Intégration des icônes pour les évaluations et autres éléments graphiques.
- **Google Fonts** : Utilisation de la police "Raleway" pour une cohérence typographique.
- **Git** : Suivi des modifications du code et versionnement via GitHub.

## Fonctionnalités principales

1. **Recherche d'hébergements** : Formulaire de recherche avec champ de saisie et filtres, permettant de rechercher des hébergements par ville (interface seulement).

2. **Affichage des hébergements et activités** : Les cartes d’hébergements et d’activités sont entièrement cliquables et présentent des images, des évaluations et des descriptions.

3. **Design responsive** : Le site s’adapte parfaitement aux différentes tailles d’écran, garantissant une expérience utilisateur fluide sur desktop, tablette et mobile.

4. **Accessibilité optimisée** : Le site est conçu pour être accessible aux utilisateurs de technologies d’assistance, grâce aux descriptions d’images et aux labels dans les formulaires.

## Installation

Pour cloner ce dépôt et exécuter le projet en local, suivez les étapes suivantes :

1. Clonez le dépôt :

   ```bash
   git clone https://github.com/troisdes/booki-starter-code.git
   ```

2. Accédez au répertoire du projet :

   ```bash
   cd booki-starter-code
   ```

3. Ouvrez le fichier `index.html` dans un navigateur pour visualiser le site.

## Auteur

Ce projet a été réalisé par **troisdes**, dans le cadre du **Projet 02** de la formation **Développeur web** d'OpenClassrooms.  
[Consultez le dépôt GitHub pour suivre l’évolution du projet](https://github.com/troisdes/booki-starter-code)
