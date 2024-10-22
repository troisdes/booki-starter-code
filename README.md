# Projet BOOKI - Intégration des maquettes en HTML & CSS

## Description

Le projet **BOOKI** est un site web fictif destiné à aider les utilisateurs à trouver des hébergements et des activités touristiques. Ce projet a été réalisé dans le cadre de la formation **OpenClassrooms** et visait à intégrer des maquettes fournies (desktop, tablette, mobile) en utilisant **HTML5** et **CSS3**.

L'objectif de cette intégration est de développer un site web responsive, conforme aux standards W3C et aux meilleures pratiques de développement, tout en assurant une accessibilité optimisée pour tous les utilisateurs.

## Structure du projet

Le projet est structuré autour des éléments suivants :

- **`index.html`** : Contient la structure sémantique du site. Le fichier HTML a été complété avec les sections sémantiques (header, main, footer) pour une meilleure organisation du contenu et un respect des standards SEO.
- **`css/style.css`** : Fichier contenant les styles CSS pour mettre en page le site. Il utilise `flexbox` et `grid` pour la disposition des éléments et inclut des media queries pour une adaptation responsive.
- **`images/`** : Ce dossier contient toutes les images nécessaires à l'interface (hébergements, activités, logo, etc.).

## Modifications et améliorations apportées

Dans le cadre de cette intégration, plusieurs ajustements et ajouts ont été effectués pour améliorer l’apparence du site, sa structure, et sa conformité :

1. **Intégration des maquettes** : Le design a été entièrement basé sur les maquettes fournies, en respectant la mise en page définie pour desktop, tablette et mobile.
2. **Responsive design** : Grâce à l’utilisation de `flexbox` et `grid`, ainsi que des media queries, le site s’adapte aux différentes tailles d’écran (desktop, tablette, mobile).
3. **Amélioration de la lisibilité** : Ajustement des couleurs et des contrastes pour garantir une bonne lisibilité sur tous les appareils.
4. **Optimisation CSS** : Réorganisation des styles avec l'utilisation de variables CSS (`:root`) pour une meilleure maintenabilité et centralisation des couleurs principales du site.
5. **Accessibilité renforcée** : Ajout de descriptions alternatives (`alt`) pour toutes les images et utilisation de labels dans les formulaires pour garantir une expérience utilisateur inclusive.
6. **Validation W3C** : Des ajustements mineurs ont été effectués pour garantir la conformité du code avec les standards du W3C.
7. **Gestion des fichiers avec `.gitignore`** : Ajout d'un fichier `.gitignore` pour éviter de versionner des fichiers temporaires et garantir la propreté du dépôt.

## Technologies utilisées

- **HTML5** : Utilisé pour structurer les pages du site de manière sémantique, en suivant les meilleures pratiques SEO.
- **CSS3** : Utilisé pour styliser les éléments du site, gérer la mise en page avec `flexbox` et `grid`, et rendre le site entièrement responsive grâce aux media queries.
- **Font Awesome** : Utilisé pour intégrer des icônes visuelles sur le site, comme les étoiles pour les évaluations des hébergements.
- **Google Fonts** : Utilisation de la police "Raleway" pour maintenir une cohérence typographique sur l’ensemble du site.
- **Git** : Utilisé pour le versionnement du code et le suivi des modifications via GitHub.

## Fonctionnalités principales

1. **Recherche d’hébergements** : Un formulaire de recherche avec filtres permet aux utilisateurs de rechercher des hébergements par ville et de choisir des catégories spécifiques (économie, familial, romantique, etc.).
2. **Affichage des hébergements, lieux populaires et activités** : Présentation des hébergements et des activités touristiques sous forme de cartes visuellement attrayantes, avec des images, des évaluations et des prix.
3. **Design responsive** : Le site s'adapte parfaitement aux différentes tailles d'écran (desktop, tablette, mobile) pour garantir une expérience utilisateur fluide sur tous les appareils.
4. **Accessibilité optimisée** : Le site est conçu pour être accessible aux utilisateurs de technologies d’assistance, grâce aux descriptions d’images, labels explicites dans les formulaires et l’utilisation d’attributs ARIA.

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
3. Ouvrez le fichier `index.html` dans votre navigateur pour visualiser le site.

## Auteur

Ce projet a été réalisé par **troisdes** dans le cadre de la formation **OpenClassrooms**.  
Consultez le dépôt GitHub pour suivre l’évolution du projet :  
[https://github.com/troisdes/booki-starter-code](https://github.com/troisdes/booki-starter-code)