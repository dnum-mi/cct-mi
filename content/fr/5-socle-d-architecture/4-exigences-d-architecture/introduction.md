---
title: Exigences d'architecture
layout: layouts/page_date_readtime.njk
showBreadcrumb: true
date: git Last Modified
eleventyNavigation:
  key: Exigences d'architecture
  parent: Socle architecture
  order: 4
---

Les exigences du CCT sont classées en 2 niveaux d’exigence (périmètre du Ministère de l’Intérieur) :

- **P**rimordial : L’exigence est impérative et traitée administrativement.
- **I**mportant : Exigence prise en compte pour la notation technique de la solution

Précisions sur le cas de l’exclusion administrative (périmètre du Ministère de l’Intérieur) :

- La non-conformité au cadre de norme entraîne l’exclusion administrative lors du dépouillement et la mise en œuvre des actions de remédiation du marché lors de l’exécution du marché.
- La non-conformité aux exigences d’architecture entraîne l’impossibilité d’utilisation du socle de sécurité associé à l’offre Cloud Native

Par défaut les règles du CCT s’imposent. Elles peuvent être précisées dans le cas d’un appel d'offres dans le règlement de consultation pour le dépouillement des offres et dans le CCAP pour l’exécution du marché. Une demande de dérogation est possible. ( cf paragraphe ad hoc )

Pour information les exigences sont organisées telles que décrites ci-dessous :

![alt_text](/img/image7.png "image_tooltip")

1. **Standards & Normes industrielles et étatiques**
   - ensemble des exigences relatives aux normes de niveau supérieur à respecter pour toute application étatique
2. **Code applicatif & Image**
   - exigences issues des [“15 factors”](https://vikasg11.medium.com/fifteen-factor-app-3dc16727ecd7) pour garantir la conception d’une application “Cloud Native”, associées aux exigences minimales permettant de s’intégrer au contexte du Ministère de l’Intérieur
3. **Modèle d’opération** 
4. **Intéractions & Flux** 
   - exigences d’intégration et d’intéraction inter-applicatives dans le contexte étatique et du Ministère de l’Intérieur
5. **Infrastructure** 
   - exigences et prérequis concernant l’infrastructure sous-jacente (notamment Kubernetes)
6. **Services mutualisés Applicatifs et d'Infrastructure** 
   - exigences d’intégration aux services centralisés du Ministère de l’Intérieur, permettant une homogénéisation de la production, un meilleur contrôle et une maîtrise de la dette technique

Les exigences sont réparties ainsi : 
- [Les exigences qui sont valables quelque soit l'offre d'hébérgement mis en oeuvre](../exigences-architecture/) 
- [Les exigences qui sont specifiques d'une mise en oeuvre sur le Cloud PI Native](../../../3-doctrine-d-hebergement/1-cloud-native/5-exigences-d-architecture/exigences-architecture/)
- [Les exigences qui sont specifiques d'une mise en oeuvre sur Cloud PI Hors approche Cloud Native](../../../3-doctrine-d-hebergement/2-cloud-pi/5-exigences-d-architecture/exigences-architecture/)
- [Les exigences qui sont spécifiques d'une mise en oeuvre au sein des SGAMI](../../../3-doctrine-d-hebergement/3-sgami/5-exigences-d-architecture/exigences-architecture/)


{%include "components/back_to_top.njk" %}