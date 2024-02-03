---
title: Cloud Pi Native - Offre CI/CD
layout: layouts/page_date_readtime.njk
showBreadcrumb: true
date: Last Modified
---


## Présentation de l’offre interMinistérielle Cloud Pi Native

L’offre Cloud PI native répond aux exigences du CCT à travers un ensemble organisationnel et technique. Elle propose une offre Cloud régalienne, souveraineté, sécurisée et isolée de toute problématique juridique extra-européenne. 

La composition de l’offre est amenée à évoluer en termes de catalogue de service selon la demande et les financements disponibles, ces évolutions permettront la diminution de la quantité de code produit par les équipes de développement et l'accélération des performances, typiquement : fonctions as services, services managés, gpu;Les offres d’hébergement compatibles avec les applications « Cloud Native » du ministère de l’intérieur sont :
- Hébergement de l’application sur les infrastructures internes infogérées ;
- Hébergement de l’application sur des infrastructures cloud externes ;
- Hébergement de l’application sur des infrastructures gérées par l’application.L’ensemble de l’administration technique de la plateforme et des infrastructures est automatisée, pilotée par le développeur/concepteur via l’orchestration DevSecOps avec mise en œuvre d’un principe dit _gitops_: la plateforme de production “tire” le déploiement.Pour rappel, le développeur n’accède pas directement à l’environnement de production. Toute correction ou évolution suit le processus de déploiement automatisé passe via le principe “gitops” évoqué ci-dessus. Le développeur dispose d’un accès libre à ses environnements (via un poste bastion si l’environnement est situé côté ministériel) il dispose également d’un accès proxifié aux indicateurs de la production. La service team qui l’accompagne, avec les accréditations nécessaires, dispose quant à elle d’un poste dédié lui permettant d’accéder directement via un bastion aux services d’observabilité et faciliter le débogage en production. (note modalité en cours d’évaluation incrémentale )


Le modèle de responsabilité est présenté ci-dessous :

![alt_text](/img/cloudnative_modele_responsabilites.png "image_tooltip")

L’ensemble du code source de l’offre Cloud PI Native et sa documentation sont disponibles en open-source sous la licence MIT. Toute contribution est la bienvenue.

![alt_text](/img/cloudnative_segmentation_hebergement.png "image_tooltip")

**Note** : chaque région est autonome dans son fonctionnement. Seul le service de stockage objet de type S3 est accessible sur l’ensemble des régions ministérielles. ( réplication en proximité dans le datacenter).

### Les magasins de composants kubernetes et d’image de base

Associée avec l’offre Cloud pi Native, des magasins de composants kubenetes sont mis à disposition incrémentalement selon les besoins des applications cela inclut celui de l’éditeur RedHat. Le développeur peut dès aujourd’hui s’appuyer sur un catalogue porté par l’Insee autour de son produit Onyxia : <https://github.com/InseeFrLab/helm-charts>

L’équipe produit est fortement invitée à l’utiliser ces composants courants et ne pas refabriquer une version dédiée dont le cycle ne sera pas en adéquation avec les besoins de réactivité en mcs.

A propos des images de base nues, il est recommandé d’utiliser les versions dites "LTS" , certifiées et maintenues selon un processus qualité au sein des communautés ou éditeurs pour la construction des pods/conteneurs. Debian, Redhat, Ubuntu font partie des communautés les plus attentives.

Sur les besoins "classiques" de persistance : postgres, redis, mariadb, mongodb, elastic, etc… l’approche recommandée de s’appuyer sur les opérateurs kubernetes disponibles et les objets statefullSet. 

Sur le cluster de production les operators sont déployés par l’hébergeur car généralement ils requièrent les droits globaux. L’équipe projet doit vérifier les versions disponibles lors de la conception de son projet.


{% include "components/back_to_top.njk" %}