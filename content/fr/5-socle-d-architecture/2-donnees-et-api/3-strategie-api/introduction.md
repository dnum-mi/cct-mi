---
title: Doctrine API -Introduction
layout: layouts/page_date_readtime.njk
showBreadcrumb: true
date: Last Modified
---

## <a name="intro">Introduction</a>

Sous l’impulsion de la Stratégie État Plateforme lancée par la DINUM, de la loi pour une République Numérique et de la [loi 3DS](https://www.economie.gouv.fr/daj/lettre-de-la-daj-application-de-la-loi-3ds-echange-de-donnees-entre-administrations), les systèmes d’information des ministères sont amenés à s’ouvrir. De même, la notion de plateforme incite à la mise en commun de données et de services de l’État dans un objectif de construction d’un écosystème d’acteurs publics ou privés. Ces derniers pourront alors les assembler pour construire ou rénover les services à destination des usagers de l’Administration.

La construction de cet État Plateforme repose sur l’utilisation d’interfaces de programmation applicative appelées API (Application Programming Interface). Cette technologie s’appuie sur des standards largement éprouvés par les géants du Web tels que Google, Amazon ou encore Twitter. Une telle plateforme permet la collaboration au sein de l’écosystème, mais également l’expérimentation de nouveaux services publics numériques dans des délais et des coûts réduits.

Ce document se veut un cadre pour la conception et la réalisation d’API. Celui-ci sera enrichi et adapté au rythme de la construction de l’État Plateforme et des retours des utilisateurs. Cette version pose les bases nécessaires aux premières réalisations. Elle n’a pas la prétention d’être exhaustive ni dans les réponses apportées, ni dans les sujets abordés.

## <a name="API">Les API</a>

Pour remplir cette promesse, les API mises en place dans le cadre de l’État Plateforme doivent pouvoir être assemblées et interopérer. Le respect des standards est un élément essentiel mais pas suffisant pour atteindre cet objectif. En effet, ils focalisent sur les aspects techniques sans explicitement adresser les besoins fonctionnels et métiers. Ce sont pourtant ces derniers qui donnent un sens à l’utilisation ou à la création d’une API.

C’est pour ces raisons qu’il est essentiel, en complément du respect des standards, de définir une stratégie claire des API répondant aux enjeux métiers. Pour cela, on s’attachera, lors de la conception d’une API, aux aspect fonctionnels et métiers des services fournis :

- format de la donnée facilitant son utilisation quelques soient les contextes;
- sollicitation au fil de l’eau (intégration dans les processus des partenaires);
- adaptation des traitements en fonction des contextes des partenaires (plage d’ouverture, pics saisonniers …);
- contrôle des données transmises adaptées aux cadres légaux et aux besoins des partenaires


## <a name="choix">Choix technologiques</a>

La stratégie État Plateforme met en avant certains standards qui sont également utilisés dans les différentes API construites par des acteurs publics et disponibles sur [api.gouv.fr](https://api.gouv.fr/) :

- l’architecture REST et [API RESTful](https://restfulapi.net/) pour l’appel et l’utilisation des API;
- [la spécification OpenAPI](https://github.com/OAI/OpenAPI-Specification) et [le framework swagger](http://swagger.io/) pour la documentation des API;
- [le format JSON](http://www.json.org/) pour la structuration des données


[Retour au sommaire](../sommaire)

{% include "components/back_to_top.njk" %}
