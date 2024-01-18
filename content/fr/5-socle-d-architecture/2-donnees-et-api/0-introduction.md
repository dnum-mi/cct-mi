---
title: services et données
layout: layouts/page.njk
showBreadcrumb: true
eleventyNavigation:
  key: services et données
  parent: Socle Architecture
  order: 2
---

# Introduction

Toute application offre des services et manipule des données, des concepts métier, qui jouent souvent un rôle plus large et plus durable que l'application elle-même. Toute application doit adresser, sans conditions, les 5 questions élémentaires suivantes :

1. [**Concevoir une application orientée service et données**](./1-donnees-et-services/) - couvert par plusieurs questions :
   -  **Réutilisation** Les données que doit manipuler mon application existent elles déjà ailleurs et ai je envisagé une réutilisation ?
   -  **Exposition des données** - L'application est elle pensée pour faciliter la réutilisation des données qu'elle crée ou transforme ?
   -  **Exposition des traitements** - Au delà d'une exposition brute de données, mes traitements sur les données eux mêmes peuvent être exposés ? Sont-ils exposés en vue d'une réutilisation possible ?
1. [**Gestion des échanges**](./2-gestion-des-echanges/) - Les échanges, internes comme externes, sont pris en charge par des dispositifs ministériels ou interministériels dédiés. Ont-ils été pris en compte ?
2. [**Analyser et valoriser les données**](./4-analyser-et-valoriser-les-donnees/) - Les données sont un patrimoine indépendamment des traitements qui leur sont appliqués. Elle doivent pouvoir être notamment croisées, analysées, anonymisées, parfois recyclées en données ouvertes. Toutes les mesures ont elles été prises pour faciliter cette valorisation ultérieure?
3. [**Données personnelles**](../socle-de-securite/donnees-personnelles)/ - Le cadre juridique relatif au traitement des données personnelles a-t-il été bien pris en compte (cf. notamment RGPD) ?
4. [**Archivage**](./6-cycle-de-vie/) - Le cycle de vie complet des données manipulées par l'application a-t-il été pensé ?
5. [**Intangilibité**](5-protection-intangibilite-non-repudiation-donnees/) - Les données sensibles, juridiques, à valeur probante sont-il bien protégés et fiabilisés?

{% include "components/back_to_top.njk" %}
