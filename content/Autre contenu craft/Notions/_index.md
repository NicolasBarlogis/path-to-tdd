---
description: ""
title: Notions
weight: 4
alwaysopen: false
---

## Entity
Une entité est définie comme ayant une identité, en plus de contenir des données. Modifie le contenu d'une entité ne change pas forcément son identité (ex: changement @ email d'un user). [Source](http://www.informatix.fr/articles/conception/valueobject-qu-est-ce-que-c-est-192)

## Value Object
Par opposition à une entité, une value object n'est définie que par son contenu. Elle est ainsi inmutable, car changer le contenu faire que le value object n'est plus le même. [Source](https://martinfowler.com/bliki/ValueObject.html)

## Arrange - Act - Assert
Méthodologie d'organisation des tests unitaires. Correspond au given - when - then en BDD. *Arrange* on prépare les données prérequises. *Act* on fait le test en lui même. *Assert* réaliser le contrôle. [Source](https://automationpanda.com/2020/07/07/arrange-act-assert-a-pattern-for-writing-good-tests/)