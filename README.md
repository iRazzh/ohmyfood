﻿## OpenClassrooms - Projet 3 - ohmyfood! :
 
### Présentation du projet : 

Troisième projet du parcours "Développeur Web" chez OpenClassrooms. L'objectif de ce projet est d'intégrer une maquette fournie, d'une page web, de manière reponsive et de la dynamiser avec des animations CSS en utilisant le préprocesseur Sass. 

![15982605908418_Maquettes Ohmyfood](https://user-images.githubusercontent.com/70963008/123450599-32b2cf00-d5dd-11eb-9212-373dc4190373.jpg)

### Eléments fournis par l'entreprise Ohmyfood! : 

- La maquette du site Ohmyfood! en résolution mobile.
- Les différentes images présentes sur la maquette du site.
- Les différentes couleurs demandées.
- La police d'écriture "Shrikhand" pour les titres & le logo.
- La police d'écriture "Roboto" pour les textes.

### Technologies : 

- Le développement devra se faire en CSS, sans JavaScript.
- Aucun framework ne devra être utlisé, en revanche, l'utilisation de Sass serait un plus. 
- Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.

### Compatibilité :

- Le site sera développé en utilisant l'approche mobile-first.
- L'ensemble du site devra être responsive sur mobile, tablette et desktop. 
- Les pages devront passer la validation W3C HTML/CSS.
- Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome & Firefox. 

### Livrables attendus :

Page d'accueil (x1) :
- Affichage de la localisation des restaurants. A terme, il sera possible de choisir sa localisation pour trouver des restaurants proches d'un certain lieu. 
- Une courte présentation de l'entreprise. 
- Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l'utilsiateur est redirigé vers la page du menu.

Pages de menu (x4) :
- 4 pages contenant chacune le menu d’un restaurant.

Footer :
- Le footer est identique sur toutes les pages.
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

Header : 
- Le header est présent sur toutes les pages.
- Sur la page d’accueil, il contient le logo du site.
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.

### Effets graphiques & animations :

Boutons : 
- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic.

Page d'accueil : 
- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

Pages de menu : 
- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.