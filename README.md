# Ohmyfood!

Projet 3 du parcours développeur web d'Openclassrooms.

L'objectif de ce projet est d'intégrer et dynamisez des pages web avec des animations CSS.

Le site de l'entreprise ohmyfood propose les menus de 4 grands restaurants parisiens. Il permettra la réservation en ligne et la composition de menus.

---

## Graphisme

### Polices

Logo et titres: Shrikhand
Texte: Roboto

### Couleurs

- Primaire: #9356DC
- Secondaire: #FF79DA
- Tertiaire: #99E2D0

---

## Technologies

- Le site est intégré uniquement en HTML et CSS.
- Aucun framework n'a été utilisé.
- Le préprocesseur SASS à été utilisé.
- Le code à été versionné sur GitHub et est accessible sur GitHub Pages.
  - https://github.com/LukasBoisson/LukasBoisson_3_01012022
  - https://lukasboisson.github.io/LukasBoisson_3_01012022/
- L'éditeur de code utilisé pour ce projet est Visual Studio Code.
  (avec les extensions Live Server et Prettier)

- Si vous récuperez les fichiers du projet pensez à installer toutes les dépendances répertoriées dans le package.json avec la commande **npm i**

## Compatibilité

Le site est responsive, il a été intégré en mobile first mais s'adapte également aux formats tablet et desktop.

---

## Livrables

- Une page d'accueil
- Quatre pages menu ont été réalisées

## Effets et animations

### Boutons

- Au survol la couleur des boutons s'éclaircie légèrement et l'ombre portée est plus visible.
- Le bouton "j'aime" en forme de coeur se rempli progressivement, actuellement fonctionne au survol.

### Loading spinner

- Proposition de design
- Il apparait pendant 3 secondes lors du chargement de la page d'accueil.

### Animations

- Sur les pages de menu les plats apparaissent progressivement avec un léger décalage dans le temps.
- Les utilisateurs pourront ajouter des plats à leur commande. Pour cela une case avec une icône apparaitra au clic pour montrer la séléction. Pour l'instant l'effet est visible uniquement au survol.
- Lorsque l'intitulé des plats est trop long il est rogné avec des points de suspension.
