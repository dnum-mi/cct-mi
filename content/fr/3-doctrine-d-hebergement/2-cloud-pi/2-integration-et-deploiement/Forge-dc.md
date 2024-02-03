---
title: Offre de déploiement et d'intégration continu (IaaS) - Forge DC
layout: layouts/page_date_readtime.njk
showBreadcrumb: true
date: Last Modified
---

# La forge DNUM[/ DC]

La forge DNUM est l'offre de service de la DNUM qui propose l'outillage nécessaire à l'intégration continue, au déploiement continu, et au suivi des projets sur les offres IaaS cloud :
- gitlab dépôt de code git des scripts de déploiement et autres configurations
- openstack, son API, et des fichiers d'architecture YAML permettant de piloter le cloud PI.
- ansible et python les langages de scripts
-  CLI forge DC l'outil en ligne de commande qui assiste l'intégrateur et l'exploitant dans l'automatisation des commandes
- gitlabrunner l'ordonnanceur utilisé pour automatiser les actions, à prendre en charge par le projet
- nexus le dépôt de binaires et proxy cache des dépôts applicatifs de l'internet (maven, npm, composer, ...)


## Les fonctions d'intégration continue de la forge DNUM

La forge DNUM permet de créer des paquetages déployables, au travers une image de contenaire de manière privilégié. Le paquetage déployable à privilégier au sein de la forge DNUM est l'image Docker stockée sur le dépôt Nexus. La reconstruction de cette image Docker et sa validation est effectuée par un pipeline gitlabrunner et des scripts Ansible. Outre ce paquetage déployable, les livrables suivant sont aussi obligatoirement présent sur le dépôt Gitlab :
- le code source de l'application
- une version incluse dans l'application (par exemple sur une page)
- unerequête runtime de test
- les scripts de build (utilisés pour construire le paquetage)
- les scripts de test introduisant des conditions d'acceptabilité des User Story et qui incluent nécessairement des conditions d'exploitabilité du déploiement

Il est possible de synchroniser la forge DNUM avec des dépôts externes au ministère de l'intérieur de manière autonome au sein de son projet, par exemple dans un pipeline d'intégration continue. Il s'agit d'opération de type "pull" et à sens unique (l'intérieur va chercher ce qu'il y a à l'extérieur). 

A cet effet, il est OBLIGATOIRE de reconstruire les binaires en interne au ministère de l'intérieur à partir des sources, des scripts, et des dépendances. Dans ces configurations hybrides (interne/externe), l'homogénéité des configurations influe sur la compatibilité développement/production. La chaîne d'intégration et notamment ses tests automatisés sont les garants de la livraison d'un paquetage déployable opérationnel en production.

## Les fonctions de déploiement continu de la forge DNUM

La fonction de déploiement de la forge DNUM s'appuie sur les images gérées par le service Glance d'OpenStack. le CAEX (cahier d'exploitation) est aussi l'un des objectif de livrable de la forge DNUM. La forge DC nécessite la mise à disposition d’un CAEX (cahier d'exploitation) par application,  quiréférence les commandes permettant de démarrer, arrêter, sauvegarder, restaurer, superviser, déclencher un PRA, ... L’équipe de la forge DC normalise et accompagne l'exploitant en simplifiant ces procédures.
D'autres outils sont enfin actuellement utilisés au delà du déploiement pour gérer l'exploitation au titre de la sauvegarde et archivage, supervision. Il est obligatoire d'en tenir compte dans les scripts de déploiement pour entrer dans le cadre de l'offre d'exploitation du ministère :
- fournir une sauvegarde régulière en précisant son emplacement, sa fréquence, sa taille et son augmentation, ses règles d'archivage, et le processus de restauration
- fournir une ou plusieurs transaction de test sous la forme d'une URL retournant l'état de fonctionnement de l'application et un message éventuel ciblant le problème relevé

## Impacts sur l'application de la Forge et de l’offre DevSecOps
Le ministère doit pouvoir conserver la maîtrise de ses applications et de ses produits, que ceux-ci soient développés en interne ou en participation avec de prestataires externes. Cette maitrise passe par la détention du code source, des licences appropriées, des scripts de compilation et de paquetage, des scripts de construction des infrastructures et de déploiement. En définitive la capacité à reconstruire complètement l'application en cas de perte.

Les usines d'intégration et de déploiement du ministère sont un moyen d'atteindre cet objectif. Celles-ci permettent par ailleurs de mettre à disposition des concepteurs des composants réutilisables.


