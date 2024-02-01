---
title: Cloud Pi Native - Contexte, enjeux et vision
layout: layouts/page.njk
showBreadcrumb: true
---


## Le contexte, les enjeux, la vision

**Audience : ce paragraphe s’adresse à tout acteur considérant l’usage de l’offre Cloud Pi Native du ministère de l’intérieur, il présente les principes fondateurs. Le cloud : des nouvelles possibilités techniques, une collaboration étendue des acteurs pour répondre aux enjeux d’un contexte exigeant, incertain et accéléré.**


À travers sa doctrine [« Cloud au centre »](https://www.numerique.gouv.fr/services/cloud/doctrine/), l’État encourage l’ensemble des acteurs publics à se saisir de son potentiel afin de développer une nouvelle génération de services numériques de qualité et qui répond au besoin dans un cadre de normes juridiques adapté à l’usage. Cela répond notamment au besoin accru d’agilité et d’efficience de l’administration.

Le Cloud est une approche d’accès à l’infrastructure d’hébergement à travers une interface standardisée et rendant abstraite et normalisée les technologies sous-jacentes. Cette abstraction permet une automatisation poussée, supprimer les frictions organisationnelles, les non-qualités et lenteurs induites par des opérations manuelles. L’infrastructure est pilotable par du logiciel et donc automatisable avec des processus reproductibles.

La technologie Cloud Native fait référence à l’usage de Kubernetes. Kubernetes est une technologie issue des travaux des grands acteurs de l’Internet il y a plus de 15 ans pour rendre encore plus efficace et sécurisée l’usage des infrastructures techniques, la résilience des hébergements et apporter une souplesse organisationnelle accrue. Les grands services de l’internet s'appuient sur cette technologie, elle permettent une résilience extrême et permet d’absorber un trafic extrêmement important. 


Les architectures des applications se simplifient avec une abstraction de plus en plus grande de l’infrastructure avec notamment la montée en puissance de services managés, fonctions-as-a-service dans l’objectif recherché de diminuer la quantité de code produite et l’objectif est de réduire charge des équipes intégrées de développement, déchargé de nombreuse problématique de gestion de l’’infrastructure de leur application.


L’ensemble des organisations ayant mis en œuvre cette technologie telle que EDF, Orange, des services de vente en ligne, des Banques, Airbus, Urssaf, etc… ont vu également leurs efficiences de l’usage du numérique augmenter, il y a un _avant et un après_.


Le ministère de l’intérieur, l’un des premiers acteurs étatiques à avoir proposé une offre Cloud il y a plus de 5 ans, étend son offre de service, en proposant l’offre Cloud Pi Native combinant une offre d'hébergement kubernetes sécurisée jusqu’au niveau DR. Cette offre est accompagnée d’un modèle DevSecOps outillé permettant une fluidité organisationnelle accrue et un renforcement de la qualité des solutions numériques.

Les approches cloud, devops et l’agilité ont progressivement permis de concilier des postures antagonistes : les développeurs ayant besoin de pouvoir déployer fréquemment, et l’exploitation ayant au contraire besoin de stabilité et de diminuer les risques liés au changement. La clé réside dans une collaboration étendue de tous les acteurs en prenant compte de la sécurité à toutes les étapes : le devops.

### Une évolution des pratiques pour un numérique efficient et éco-responsable et réactif

Les contraintes s’accentuent sur la production de services numériques, le standard de qualité général a augmenté massivement avec les acteurs du net et industrielle qui produisent des solutions ergonomiques, sécurisées qui montent à l’échelle facilement. Un fossé important s’est creusé entre l’efficience du numérique ‘legacy’ et ce monde moderne. 

L’environnement change rapidement, il devient incertain, il faut réagir de plus en plus rapidement, la pression augmente sur la production de solutions numériques ergonomique, nécessitant des cycles raccourcis, la prise en compte de l’éco responsabilité, de l’accessibilité et le maintien d’un haut standard de qualité et de sécurisation. 

Seul un changement majeur de pratiques s’appuyant sur l’opportunité du Cloud Native ( kubernetes ) et du DevSecOps permettent de satisfaire ce nouveau standard d’exigences.

Le mode produit et l’agilité sont indispensables en complément de l’utilisation du cloud, extrait de la doctrine cloud au centre:

“ _L’adoption du cloud doit s’accompagner de celle des pratiques associées à l’excellence dans la production de services numériques (proximité entre métiers et équipes informatiques, scalabilité, agilité, « devops », « continuous delivery » qui sont les garants de l’adaptation des produits à leurs utilisateurs) ;  “_

### Les principales caractéristiques du modèle opérationnel Cloud Native

Le fonctionnement évolue vers la suppression de la fragmentation des responsabilités dans la chaîne de production et l’automatisation de celui-ci. (cf mode2 proposé par le Gartner) 

**L’équipe projet intégrée (équipe produit) voit ses prérogatives étendues**
* Elle est organisée autour du produit numérique livré. Elle fonctionne en modalité intégrée et de manière autonome en lien avec la vision et les contraintes fixées. 
* Elle est composée de développeurs, architectes, ergonome (ux-design), juriste, gestionnaire du changement, etc… orchestrée par le product owner et généralement facilité par un coach / scrum master agile. Elle est focalisée sur l'ergonomie, la qualité et la performance de la solution mise à disposition des usagers. C’est le modèle **«You build it, you run it, you support it »**. (vous l’avez construit vous l’opérez )
* Une équipe d’aide appelée “service team” qui peut être temporaire ou permanente selon la taille de produit est chargée de mettre en place l’automatisation et les environnements de travail et de production. Cette dernière doit être aguerrie à ces technologies et l’offre cloud native.

**L’hébergeur assure quant à lui**, la mise à disposition d’une offre de service hautement disponible et sécurisée. L’usage de l’offre est réalisé via une console, une interface technique normée (API), une documentation et des exemples accélèrent la prise en main.

Il assure également la fourniture de services d’abstraction tels que des services managés ou fonctions as a service, un pipeline devsecops etc…

**L’équipe intégrée est autonome et travaille sans échange avec l’hébergeur**.

La console mise à disposition assure ce lien avec une documentation associée. L’ensemble des opérations réalisées manuellement auparavant lors des étapes d’élaboration sont complètement automatisées. Le code logiciel est testé en permanence et automatiquement par un outillage : l’orchestrateur DevSecOps. 

Pour assurer la qualité du code, plusieurs principes sont mis en œuvre, une couverture de test (100% sur le back-end), l’analyse statique du code, l’analyse récursive de vulnérabilité des composants importés (librairie, images ), des tests de sécurité et de performances, tests spécifiques liés à des besoins de vérifications particulières.

L’équipe de développement est prévenue au plus tôt par l’orchestrateur DevSecOps en cas de non-qualité. L’orchestrateur offre des options techniques pour intégrer les retours dans le flux de travail du développeur afin de procéder à la correction au plus tôt des anomalies, cette modalité s’appelle “shift-left”. Infine, seul un logiciel ayant atteint le niveau de qualité fixé peut être déployé.  

Les développeurs assurent continuellement la qualité et la sécurité du code produit, la non-régression et l'absence de vulnérabilité soutenus par l’outillage mis en place, la chaîne devsecops, les environnement de codage (IDE) et gestionnaire de code deviennent de plus en plus en plus performant et identifient dès l’écriture ou l’intégration du code les erreurs d’algorithmies ou si un secret est laissé dans le code. 

Les architectures sont modulaires et les composants internes ainsi que les interfaces entre applications sont découplées, c’est à dire rendus indépendants techniquement et organisationnellement via des interfaces normées (APi). Cela permet la maintenance et les  évolutions indépendantes entre composants. Ce découplage contribue fortement à réduire le coût des changements et faciliter les transitions technologiques en cas d’obsolescence.

La conception de l’architecture, le choix des langages sont faits pour une efficience de l’usage des ressources d’infrastructures et également sur l’impact sur le poste de travail.

La conteneurisation, l'élasticité dynamique de la solution d'orchestration de conteneurs kubernetes, la mutualisation des infrastructures physiques soutiennent fortement cette  efficience. Le non-respect de ce principe de modularité a été identifié par la direction interministérielle du numérique comme l’une des causes d’échec des grands programmes de l’État. La modularité, l’indépendance technique et organisationnelle des modules lors du déploiement, permettent de réduire la taille des déploiements ce qui contribue à réduire les risques et fluidifier les mises en production. Les déploiements peuvent ainsi être rendus transparents pour  des usagers et les retours arrière éventuels sont  facilités. Il est ainsi possible de déployer en confiance, plusieurs évolutions par jour si nécessaire.

L’automatisation permet de  mieux contrôler et rendre les actions prédictibles, faciliter la reprise en cas d’incident et minimiser les coûts de maintien en conditions opérationnelles et de sécurité des applications. Plus aucune intervention manuelle n’est effectuée sur les environnements ce qui permet de réduire la variance, les non-qualités, et aussi de (re)construire très rapidement des plateformes.

In fine, la conception doit s’inscrire dans une démarche d’éco-conception et de sobriété numérique des conceptions (green IT)  permettant un usage plus efficient des ressources  qu’elles soient RH, financières. L’État devant être exemplaire. cf guide d’éco-conception.


{% include "components/back_to_top.njk" %}