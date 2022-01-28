---
description: ""
title: Notions
weight: 1
---

## Design / architecture
### Entity
Une entité est définie comme ayant une identité, en plus de contenir des données. Modifie le contenu d'une entité ne change pas forcément son identité (ex: changement @ email d'un user). [Source](http://www.informatix.fr/articles/conception/valueobject-qu-est-ce-que-c-est-192)

### Value Object
Par opposition à une entité, une value object n'est définie que par son contenu. Elle est ainsi inmutable, car changer le contenu faire que le value object n'est plus le même. [Source](https://martinfowler.com/bliki/ValueObject.html)

### Event Sourcing
Pattern qui porpose de se concentrer sur la séquence de changement de l'état d'une application/d'un composant plutôt que de se contenter de l'état actuel/final. [Source](https://blog.engineering.publicissapient.fr/2017/01/16/event-sourcing-comprendre-les-bases-dun-systeme-evenementiel/#:~:text=Qu'est%2Dce%20que%20l,%C3%A9tat%20o%C3%B9%20elle%20se%20trouve.)

### Command Query Responsibility Segregation (CQRS)
Principe d'architecture séparant les query (lecture) des commandes (écriture). Cela permet nottamment de découpler les deux fonctions. [Source](https://www.insidegroup.fr/actualites/cqrs/)

---

## Canvas
### Aggregate Design Canvas
Canvas aidant à cadrer un aggrégat dans le cadre de la modélisation d'un domaine (DDD). [Source](https://github.com/ddd-crew/aggregate-design-canvas)

### Suppliers, Inputs, Process, Outputs, Customers (SIPOC)
Diagramme matérialisant un process business. Assez haut niveau.
[Source](https://searchcio.techtarget.com/definition/SIPOC-diagram-suppliers-inputs-process-outputs-customers#)

### Value Stream Mapping (VSM)
Outil qui recense visuellement l’ensemble des activités, celles à valeur ajoutée (VA) et celles à non valeur ajoutée (NVA), nécessaires à la production.
[Source](https://www.manager-go.com/organisation-entreprise/articles/vsm)

---

## Modélisation
### C4 model
Découpage en 4 étages d'une architecture logicielle (Contexte, container, composants & code), décrivant l'archi de très haut niveau et en zoomant à chaque couche, jusqu'au code. Encourage la documentation as code, via de nombreux outils permettant le diagrams as code pour du C4. [Source](https://c4model.com/)

---

## Testing
### Arrange - Act - Assert (AAA)
Méthodologie d'organisation des tests unitaires. Correspond au given - when - then en BDD. *Arrange* on prépare les données prérequises. *Act* on fait le test en lui même. *Assert* réaliser le contrôle. [Source](https://automationpanda.com/2020/07/07/arrange-act-assert-a-pattern-for-writing-good-tests/)

### Test && commit || revert (TCR)
Approche visant à améliorer la technique des développeurs (coder mieux, micro-incréments, etc...). Automatiquement ou non, à chaque fois que les tests sont joués, si ils passent le code est commité, sinon on revert et il faut recommencer [Source](https://blog.myagilepartner.fr/index.php/2019/02/18/tests-tcr-test-commit-revert/)

### Partitions d'équivalence
Résultat d'une méthode consistant à déterminer les ensembles (partitions) de valeurs d'entrée et/ou de sortie, de façon à faire moins de tests redondants et à ne pas oublier de cas. [Source](https://latavernedutesteur.fr/2018/09/06/techniques-basees-sur-les-specifications-1-7-les-partitions-dequivalence/)

---

## Refactoring
### Bubble Context
Une méthode pour refactoriser une appli legacy vers du DDD. [Source](https://www.domainlanguage.com/ddd/surrounded-by-legacy-software/)

---

## Modèles de maturité
### Capabilities Accelerate
Étude ([livre](https://www.oreilly.com/library/view/accelerate/9781457191435/)) sur les entreprises efficaces en dévelopement, dont est sortie une liste de 24 *capabilities*, listant les points communs de ces entreprises efficaces. [Source](https://devopsefficiency.com/matrices.html)

### Spotify Health check
Méthode d'assessment d'équipe, pouvant servir pour évaluder leur maturité sur certaines pratiques. [Source](https://engineering.atspotify.com/2014/09/16/squad-health-check-model/)

---

## KPIs
### Defect Removal Efficiency (DRE)
Indicde du nombre de problèmes detectés en production par rapport au nombre total de problèmes detectés. [Source](https://performance-objectives.com/kpi-defect-removal-efficiency-dre/)

---

## Bonnes pratiques
### Règles qualité web Opquast
Ensemble de centaines de bonnes pratiques web, dans un format digeste. [Source](https://checklists.opquast.com/fr/assurance-qualite-web/). [Autres checklists Opquast](https://checklists.opquast.com/fr/assurance-qualite-web/download/)