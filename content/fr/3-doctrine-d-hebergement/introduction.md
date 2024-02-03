---
title: Doctrine d'hébergement
layout: layouts/page.njk
showBreadcrumb: true
date: Last Modified
eleventyNavigation:
  key: Doctrine d'hébergement 
  parent: Offres d'hébergement
  order: 1
---

Le Ministère de l'Intérieur propose plusieurs offres d'hebergement et de services qui leur sont spécifiquement rattachés.

## L'offre d'hébergement Cloud PI
Cloud PI est une offre de cloud computing dédiée aux services de l'État, opéré par le ministère de l'Intérieur.

Elle offre la particularité de pouvoir héberger des produits manipulant des données de type diffusion restreinte (DR).

L'offre initiale est orientée infrastructure à la demande.

Elle est basée sur les technologies open source OpenStack et est hébergée dans les centres de production informatique de l'État.

Les objectifs de l'offre Cloud Pi sont les suivants :
- Fournir un cloud sécurisé et souverain pour les services de l'État,
- Contribuer à la transformation numérique de l'État,
- Réduire les coûts d'infrastructure des services de l'État.

Cette offre peut être utilisée telle qu'elle. Le détail de l'offre, les services dipsonibles et les exigences d'usages sont décrits ci-après [lien].

... ou bien complétée des supports technologiques Cloud Native. C'est l'objet du chapitre suivant.

## L'offre d'hebergement Cloud Native
L'offre Cloud Pi Native est une offre de cloud computing basée sur les technologies cloud natives, notamment OpenShift. 

Elle est proposée en plus de l'offre Cloud Pi de base, qui est basée sur OpenStack.

L'offre Cloud Pi Native offre les avantages suivants :
- Une meilleure évolutivité et agilité,
- Une plus grande facilité de développement et de maintenance,
- Une réduction des coûts.

L'offre Cloud Pi Native est destinée aux services de l'État qui souhaitent développer et déployer des applications cloud natives. 

Le CCT précise les points suivants :
- [Le Cloud Native, son contexte, les enjeux et la vision,](../../3-doctrine-d-hebergement/1-cloud-native/1-cct-cloud-native/2-contexte-enjeux-vision/)
- [L'offre Cloud Native disponible,](../../3-doctrine-d-hebergement/1-cloud-native/2-integration-et-deploiement/offre-interministerielle-cloud-pi-native/)
- [Les modalités d'intégration et d'exploitation,](../../3-doctrine-d-hebergement/1-cloud-native/2-integration-et-deploiement/integration-deploiement/)
- [Les modalités d'hebergement,](../../3-doctrine-d-hebergement/1-cloud-native/3-hebergement-et-exploitation/hebergement-exploitation/)
- Les aspects 
  - [supervision,](../../3-doctrine-d-hebergement/1-cloud-native/3-hebergement-et-exploitation/supervision/)
  - [stockage et sauvegarde,](../../3-doctrine-d-hebergement/1-cloud-native/3-hebergement-et-exploitation/stockage-sauvegarde/)
  - [sécurité des biens et des échanges,](../../3-doctrine-d-hebergement/1-cloud-native/4-securite/securite/)
- Les [exigences SSI et les attentes en vu de l'homologation des solutions,](../../3-doctrine-d-hebergement/1-cloud-native/4-securite/SSI-et-homologation/)
- Les [exigences d'architecture](../../3-doctrine-d-hebergement/1-cloud-native/5-exigences-d-architecture/exigences-architecture/)
 



## L'offre d'hebergement en SGAMI

Certains projets de developpement dans, et pour, les territoires peuvent être elligibles aux offres d'hebergement en SGAMI. 
Ceux-ci proposent une offre d'hébergement riche en services disponibles pour ces projets.

Le détail de l'offre, les services dipsonibles et les exigences d'usages sont décrits ci-après [lien].

## Les autres offres de Cloud

### L'offre de Cloud interministeriel Nubo
Une offre équivalente au Cloud Pi est l'offre Nubo, opérée par la Direction générale des finances publiques (DGFiP).

Cette offre est également basée sur les technologies open source OpenStack et est hébergée dans les centres de production informatique de l'État.

L'offre Nubo offre les mêmes services que l'offre Cloud Pi, à savoir :
- Instances de serveurs
- Stockage
- Réseau
- Services de gestion

Elle est également destinée aux services de l'État qui souhaitent héberger des données de type diffusion restreinte (DR).
Elle propose en sus des services spécifiques pour le traitement des données fiscales et sociales. Elle est donc destinée pour les developpements de solutions applciatives avec des besoins specifiques en matière de finances publiques.

### Les offres de Cloud privé
Certains projets developpement informatique peuvent être éligibles aux offres de Cloud Privé estampilés SecNumCloud. 

Les offres de Cloud privés estampillés SecNumCloud sont des offres de services de Cloud computing privé qui ont été qualifiées par l'ANSSI (Agence nationale de la sécurité des systèmes d'information). Cette qualification atteste que ces offres répondent aux exigences de sécurité de l'ANSSI, notamment en matière de confidentialité, d'intégrité et de disponibilité des données.

Les offres de Cloud privés estampillés SecNumCloud sont admissibles pour les projets de developpement logiciel qui ont besoin de garantir un niveau de sécurité élevé pour leurs données. 

Elles peuvent être utilisées pour héberger des données sensibles, telles que des données personnelles, des données confidentielles d'entreprise ou des données stratégiques.

Cependant, ces offres présentent également quelques inconvénients, notamment :
- Un coût plus élevé que les offres de Cloud public
- Une complexité de mise en œuvre et d'interoperabilité avec les services internes (SSO, services d'annuaire, ...)
- Une dépendance à un prestataire de services Cloud et à sa technologie mise en oeuvre (donc un coût à intégrer si l'application doit être un jour migrée dans un Cloud public)

La liste des [offres Cloud Privée estampillées SecNumCloud est disponible ici](http://lien).


{%include "components/back_to_top.njk" %}