---
description: ""
title: Golden Master
weight: 5
---

Le **Golden Master** est une méthode de refactoring de code dépourvu de tests. Il consiste à récupérer l'output du code existant sur un grand nombre de cas, puis a écrire des tests comparant ces outputs au résultat retourné par le code actuel.

Ces tests servent de base pour s'assurer de la non régression du refactoring.
<!--more-->

Une méthode d'application du Golden Master est l'utilisation du [Property Base Testing](/path-to-tdd/affinage/approches-spécifiques/property-based-testing/). On passe l'ancienne implémentation en propriété testée, avec pour assertion de comparer le résultat de l'ancienne implémentation (du test), avec la nouvelle implémentation.

---
## Sources
 * Badinier, G (201?) *'Tout ce qu’il faut savoir sur Golden Master Testing'*.
  [Voir l'article](https://www.softfluent.fr/blog/tout-ce-quil-faut-savoir-sur-golden-master-testing/) (consulté le 17 décembre 2021)  