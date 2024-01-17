---
title: Publication du CCT
layout: layouts/page.njk
showBreadcrumb: true
---


# Manuel de publication du CCT

## Génération et publication sur  l'Intranet du MIOM

La génération du site web et sa publication sur l'Intranet du MIOM se fait immédiatement après modification des contenus et validation des mises à jour par les acteurs responsables. 

La génération est immédiate après la réalisation d'un pull request d'intégration de la branche clonée incluant les modifications apportées par le responsable du contenu qui a créé cette branche.

Un tag avec la date et l'heure du jour de génération (yyyymmjj_hhmmss) est alors produit. La version ainsi générée est documentée des éléments qui ont été intégrés (reprise de l'argumentaire issu du pull request).

Le site Web et les contenus au format pdf sont alors générés.

Les contenus web sont déployés instantanément sur le site web Intranet. 

Les contenus au format pdf sont rendus disponibles sur le site.

Les acteurs internes peuvent alors accéder au nouveau contenu mis en ligne sur l'Intranet pour le consulter et pousser au travers des issues les besoins de corrections. 

Le responsable de contenus en prend connaissance et réalise les modifications nécessaires.


## Génération et publication sur Internet
Après corrections apportées par le responsable des contenus, et validation par l'équipe d'Architecture d'Entreprise, un tag avec l'intitulé "officiel" est alors produit. 

Les contenus du site web sont alors déployés sur l'Internet.

{%include "components/back_to_top.njk" %}