[![Deploy Eleventy with GitHub Pages dependencies preinstalled](https://github.com/dnum-mi/cct-mi/actions/workflows/Deploy%20Eleventy%20with%20GitHub%20Pages_dependencies_preinstalled.yml/badge.svg)](https://github.com/dnum-mi/cct-mi/actions/workflows/Deploy%20Eleventy%20with%20GitHub%20Pages_dependencies_preinstalled.yml)


# Le Cadre de Cohérence Technique

## Contexte

Le CCT 3.1.0 a permis d'intégrer des évolutions majeures concernant l'ENT, le référentiel des produits (ex: utilisation de docker en production, signature électronique), et l'arrivée du chapitre Cloud PI Native.

Ce CCT souffre de quelques lacunes dont les exigences doivent permettre de les corriger.

## Exigences

- Le système doit appliquer le design system de l'Etat(dsfr); 
- Le système doit permettre une recherche de mots ou groupe de mots sur l'ensemble du site;
- Le système doit être conçu pour qu'il puisse s'exécuter nativement sur Openshift/Kubernetes<sup>1</sup>;
- La prise en compte des demandes utilisateurs se fait par issues depuis un dépôt Git;
- Les référents d'un chapitre/thèmes soumettent des évolutions ou corrections via une pull/request sur le dépôt Git;
- Les documents, chapitres, thèmes sont rédigés sous forme de markdown;
- :warning: Derni0ère exigence : certains contenus doivent être convertis en pdf en vue du cctp.

[1]: il s'agit plus d'une opportunité que d'une exigence. L'instanciation sur K8s nous permet d'envisager une exposition aussi bien sur le RIE que sur internet dans l'éventualité où le repository soit uniquement exposable en interne.

## Choix

Pour répondre à ces exigences notre décision s'est portée sur [eleventy dsfr](https://ecoresponsable.numerique.gouv.fr/publications/boite-outils/fiches/eleventy-dsfr/).

## Tests réalisés

- prendre les fichiers markdown de l'ENT, données et api;
- référencer le cct cloud pi native;
- convertir le document chapeau document en markdown adapté à la lecture depuis un site;
- définir une cinématique et présentation des thèmes/chapitres en lien avec le document ou la page dit "chapeau";
- générer une image docker du site cct;
- mode d'exposition:
  - configuration d'un environnement k8s sur un "bac à sable" cloud;
  - via [github pages](https://dnum-mi.github.io/cct-mi/)
- être référencé sur une instance matomo
  
## Avantages

- site au standard dsfr;
- un module de recherche;
- une sonde **matomo** pour permettre la mesure d'audience(tester sous k8s à partir de [matomo helm](https://bitnami.com/stack/matomo/helm));

## Contraintes

Une adaptation des fichiers markdown est nécessaire. 

### sur le bas et haut de page

#### Haut de page

- sans menu:

```yaml
---
title: données et api
layout: layouts/page.njk
showBreadcrumb: true
---
```

ou

```yaml
---
title: données et api
layout: layouts/page_date_readtime.njk
showBreadcrumb: true
date: git Last Modified
---
```

> Le layout personnalisé inclue la date de publication et le temps de lecture

- référencement dans un menu:

```yaml
---
title: Pour commencer
layout: layouts/page.njk
showBreadcrumb: true
eleventyNavigation:
  key: pour commencer
  parent: Documentation
  order: 1
---
```

ou

```yaml
---
title: Pour commencer
layout: layouts/page_date_readtime.njk
showBreadcrumb: true
date: git Last Modified
eleventyNavigation:
  key: pour commencer
  parent: Documentation
  order: 1
---
```

> Le layout personnalisé inclue la date de publication et le temps approximatif de lecture

#### bas de page

```
{%include "components/back_to_top.njk" %}

```
### sur les tableaux

La représentation sous forme de markdown n'est pas trés lisible

- avec une structure 

![](https://storage.gra.cloud.ovh.net/v1/AUTH_0f20d409cb2a4c9786c769e2edec0e06/padnumerique/uploads/d6a60397-6f95-4ed9-a5f4-e1a883663e39.png)

```
{% from "components/component.njk" import component with context %}
{{ component("table", {
    title: "Critères retenus pour la sélection des logiciels, outils ou services",
    headers: ["Critères", "Attentes"],
    data: [
        ["Type de logiciel – Libre / Gratuiciel / Payant ", "Ré-utilisabilité, scalabilité, flexibilité, sécurité (transparence du code source), évolutivité (mutualisation possible des améliorations), pérennité, interopérabilité (usage des formats ouverts), limite d’usage si gratuiciel et coût à prévoir si logiciel payant."],
        ["Existence d’un support correctif O/N", "Garantie d'assistance continue, mises à jour régulières aux fins d'amélioration de fonctionnalités et de corrections de bugs, permettant ainsi une stabilité d’usage sur le long terme. Un logiciel non supporté n’a plus vocation à être utilisé sur les postes du MIOM du fait de la non couverture de ses failles de sécurité."],
        ["Outil utilisé en Interministériel O/N", "Facilité d’usage entre les systèmes utilisés dans d'autres administrations, possibilité de mutualisation en termes de support et de maintenance, partage des bonnes pratiques."]
    ]
}) }}

```

- avec une structure markdown

![](https://storage.gra.cloud.ovh.net/v1/AUTH_0f20d409cb2a4c9786c769e2edec0e06/padnumerique/uploads/677822ea-7b36-4303-8cda-a7d7824e62b4.png)



### Traitement des liens 
La suppression de l'extension .md car le site est déjà en html.
Ajouter le caractère "/" à la fin des URL (ex : ../sommaire/).

### pdf
pas de pluggins connus qui permettent la transformation de md en pdf

# Liens
Nous utilisons :
- le template fournis par [eleventy-dsfr](https://github.com/codegouvfr/eleventy-dsfr) avec une adaptation concernant l'usage de mermaid.
- [unDraw](https://undraw.co/search) pour certaines images
- [icons](https://icon-sets.iconify.design/)
