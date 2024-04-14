# Workshop technique CodeWorks - 15/04/2024

## Présentation
Ce workshop est tiré du kata [Gilded Rose](https://github.com/emilybache/GildedRose-Refactoring-Kata/tree/main/TypeScript). 

Gilded Rose est une taverne proposant divers produits. Le tavernier a donc demandé à un certain Leeroy de lui créer un outil de gestion d'inventaire.
Aujourd'hui la taverne vend les produits (Items) suivants:
  + Aged Brie
  + +5 Dexterity Vest
  + Backstage passes to a TAFKAL80ETC concert
  + Sulfuras, Hand of Ragnaros

Chaque produit a un nom (name), un délai de vente (sellIn) et un niveau de qualité (quality). Pour la plupart des produits, chaque jour qui passe dégrade leur qualité et décrémente leur délai de vente. Passé le délai de vente, la qualité évolue deux fois plus vite.

Jusqu'alors le tavernier était satisfait de son outil, toutefois il souhaite rajouter un nouveau produit: Conjured Mana Cake. Malheureusement, cela nécessite l'intervention d'un expert comme Leeroy, mais ce dernier est depuis longtemps parti en quête de nouvelles aventures.

## Objectif
Discussion / mise en place d'une stratégie de test en vue d'une refacto

## Déroulé de l'exercice
Le/la Candidat.e sera chargé.e de préparer, voire de faire la refacto du code legacy. L'exercice consiste ici à intervenir sur une base de code existante non-testée et devant être modifiée pour accuellir de nouvelles fonctionnalités.
Un.e des CodeWorkers aura le rôle de PO et donc disposera de la connaissance métier nécessaire pour que le/la candidat.e s'approprie la base de code.

## Stack Technique
  + Typescript
  + Jest

## Architecture du projet
Tous les fichiers sources sont dans le dossier "src" et les fichier de test dans le dossier "tests".

## Commandes notable
```bash
npm install #installer les dépandances du projet
npm run dev #lancer le script ./src/index.ts
npm test    #lancer les scripts de tests
```
