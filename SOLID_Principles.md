# SOLID
Il s'agit de bonnes pratiques permettant de rendre une application plus souple au niveau de la maintenance et permet d'assurer une certaine qualité de code.

## S pour Single Responsability principle
**Single Responsability** ou **responsabilité unique** définit le fait qu'une classe ne devrait être modifiée que pour une seule raison.

## O pour Open / Closed principle
La classe doit être **ouverte aux extensions** et **fermée aux modifications**. Pour éviter de faire toutes sortes de modifications il est préferable d'utiliser les interfaces.

## L pour Liskov substitution principle
Un classe mère **T** doit pouvoir se faire substituer par une classe fille **U**.

## I pour Inteface Segregation principle
**Interface Segregation** ou la **segrégation d'interfaces** suggère que la classe ne devrait pas implémenter une interface qu'elle n'utilise pas pleinement. Il est préférable d'avoir une hiérarchie d'interfaces qui décrit mieux une fonctionnalité et de n'implémenter que du nécessaire.

## D pour Dependency injection principle 
**Dependency injection** ou **injection de dépendances**, les modules de haut niveau ne doivent pas dépendre des modules de bas niveau, les astractions ne doivent pas dépendre des détails.