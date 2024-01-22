---
title: Données et API
layout: layouts/page.njk
showBreadcrumb: true
eleventyNavigation:
  key: Données et API
  parent: Socle architecture
  order: 2
---

# Introduction

Toute application offre des services et manipule des données, des concepts métier, qui jouent souvent un rôle plus large et plus durable que l'application elle-même. 

La [Doctrine API](../../2-donnees-et-api/3-strategie-api/sommaire.md) décrit les principes, les pratiques et les règles que les développeurs doivent suivrent pour garantir que les API sont conçus développées et maintenues de manière cohérente et efficace.

Toute application doit, de plus, adresser, sans conditions, les questions élémentaires suivantes :

1. [**Concevoir une application orientée service et données**](../1-donnees-et-services/) - couvert par plusieurs questions :
   -  **Réutilisation** Les données que doit manipuler mon application existent elles déjà ailleurs et ai je envisagé une réutilisation ?
   -  **Exposition des données** - L'application est elle pensée pour faciliter la réutilisation des données qu'elle crée ou transforme ?
   -  **Exposition des traitements** - Au delà d'une exposition brute de données, mes traitements sur les données eux mêmes peuvent être exposés ? Sont-ils exposés en vue d'une réutilisation possible ?
1. [**Gestion des échanges**](../2-gestion-des-echanges/) - Les échanges, internes comme externes, sont pris en charge par des dispositifs ministériels ou interministériels dédiés. Ont-ils été pris en compte ?
2. [**Analyser et valoriser les données**](../4-analyser-et-valoriser-les-donnees/) - Les données sont un patrimoine indépendamment des traitements qui leur sont appliqués. Elle doivent pouvoir être notamment croisées, analysées, anonymisées, parfois recyclées en données ouvertes. Toutes les mesures ont elles été prises pour faciliter cette valorisation ultérieure?
3. [**Données personnelles**](../../../6-socle-de-securite/donnees-personnelles/) - Le cadre juridique relatif au traitement des données personnelles a-t-il été bien pris en compte (cf. notamment RGPD) ?
4. [**Archivage**](../6-cycle-de-vie/) - Le cycle de vie complet des données manipulées par l'application a-t-il été pensé ?


{% include "components/back_to_top.njk" %}
