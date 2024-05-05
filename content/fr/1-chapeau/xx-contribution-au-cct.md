---
title: Contribuer au CCT
layout: layouts/page_date_readtime.njk
showBreadcrumb: true
date: git Last Modified
eleventyNavigation:
  key: Contribuer au CCT
  parent: À propos
  order: 5
---

# Manuel de contribution au CCT

La contribution au CCT se veut largement ouverte.
Pour atteindre ce but, le contenu du CCT a été placé dans la forge de la DTNUM.
La précedure de contribution s'appuie sur les fonctions et principes classiquement utilisés dans ce dépôt.
Il existe deux niveaux de contribution développés dans ce document : 
- Le gestionnaire de contenu [éditeur], qui édite les documents dont il a la charge,
- les parties prenantes [commentateur], qui n'accèdent pas directement aux documents, mais qui peuvent commenter via des fils de discussion appelés "issues". Ceux-ci doivent explicitement decrire les éléments à modifier ou rajouter pour que le gestionnaire de contenu puisse les prendre en compte.

## Accès à la forge et enrôlement sur le dépôt Git
La [forge DTNUM](https://gitlab.forge-dc.cloudmi.minint.fr) est accessible via les SSO du ministère. 
Lors de votre première connextion, votre accès au Depôt du CCT est positionné par défaut sur le rôle de **Commentateur**[Guest]. 

Les responsables de contenus sont des personnes mandatées en Comité CCT et doivent être enrôlés comme **éditeur**[Reporter].
Pour vous enrôler en tant qu'éditeur, en cas de changement d'organisation par exemple, vous devez en faire la demande auprès des gestionnaires du CCT [cct@interieur.gouv.fr](mailto:cct@interieur.gouv.fr).


## Contribution du commentateur
### Qui : Les parties prenantes sur chaque contenu
Certains contenus sont à contextualiser vis à vis d'autres organisations rattachés au MIOM.

Les gestionnaire de contenus ont pour charge de collecter et d'intégrer les éléments qui seraient propres à ces parties prenantes (ex. les SSO mis en oeuvres dans les différentes entités organisationnelles) dans les fiches du CCT.

D'autres acteurs peuvent soumettre au travers de requêtes (nommées Issues dans l'espace GIT) des propositions de modification (ex. ajout/remplacement/suppression d'un produit destiné à être utilisé dans un environnement de travail, un outil d'exploitation, etc...) que le gestionnaire de contenu devra analyser et intégrer le cas échéant dans sa documentation.


### Comment : modalités de dépot de contribution

{% from "components/component.njk" import component with context %}
{{ component("table", {
    title: "",
    headers: ["Action", "Description"],
    data: [
        ["Connexion au dépôt CCT", "Connexion avec son SSO, Recherche du dépôt [CCT-mi]."],
        ["Accèder à la page des fils de discussion [Issues]", "Dans le menu de gauche du dépôt CCT, choisir l'item [Issues]. Noter que ces fils de discussion sont organisés en [Open] : Nouvelles, à traiter, [Closed] : traitées, fermées"],
        ["Créer son nouveau fil de discussion", "Cliquer sur [New Issue]. Compléter le formulaire (Titre : Fiche ciblée - synthèse de la requête / Description : argumentaire voulu (texte à intégrer, ...)). Soumettre la requête [submit issue]."],
        ["Suites données", "Le responsable du contenu ciblé prend en compte la requête et l'analyse.Après analyse, il sera le seul à arbitrer sur sa prise en compte dans les prochaines versions officielles du CCT."]
    ]
}) }}


## L'édition de contenu

### Qui : Le gestionnaire de contenus
Le CCT est composé d'un ensemble de contenus organisés et dont les porteurs au sein de la DTNUM ont été identifiés. 

Ces porteurs ont pour charge de mettre et de maintenir les contenus qui leur incombent à jour.

Ces porteurs s'engagent à verifier et à modifier, le cas échéant, leurs contenus tous les trois mois.


### Comment : Modalités de saisie

Le responsable peut se connecter sur le dépôt git du CCT. Le rôle d'**éditeur**[reporter] lui est attribué.

{% from "components/component.njk" import component with context %}
{{ component("table", {
    title: "",
    headers: ["Action", "Description"],
    data: [
        ["Connexion au dépôt CCT", "Connexion avec son SSO, Recherche du dépôt [CCT-mi]."],
        ["Créer sa branche de modification", "ce positionner sur la branche [Master], puis appuyer sur le symbole [+], puis [new branch]. Créer une branche en indiquant la fiche modifiée et datée (ex. 20231201_ENT Agent)"],
        ["Choisir et éditer la fiche que vous souhaitez modifier", "En naviguant sur votre branche (s'assurer que dans l'url le nom de votre branche est bien le bon), se positionner sur le fichier a modifier et cliquer sur l'icone du stylo [Edit this file]. Vous accédez au contenu modifiable de la fiche, en language markdown. Après toute modification, penser a enregistrer les modifications dans votre branche en cliquant sur [commit changes](Penser à décrire les modifications apportées au document)"],
        ["Soumettez votre proposition de modification", "Lorsque toutes les modifications apportées à vos contenus sont réalisés, realiser un pull resquest[New pull request] de votre branche vers la branche [Main].(Penser à reporter toutes les modifications apportées a vos documments modifiés dans votre branche). Le contenu soumis passe alors par l'étape de génération du site web pour une publication immédiate sur le site web intranet du CCT. Avant publication sur le site web internet du CCT, le contenu global sera analysé par l'équipe d'architecture d'entreprise pour s'assurer de la cohérence d'ensemble. Le cas échéant, il vous demanderont de corriger la fiche. Le contenu validé par l'équipe sera ensuite poussé vers l'étape de génération du site web Internet pour publication."]
    ]
}) }}


## Processus complet d'intégration et de publication
Le processus est le suivant : 

<pre class="mermaid">
     flowchart TD
    A[Collecte] --> B[Mise à jour]
    A -->|nouveau besoins ou changements demandés| A
    B -->|Generation et publication du site | C[Site test intranet]
    C --> E[Contrôle de cohérence]
    E -->|correction nécessaire| A
    E -->|validation| F[Generation et publication]
    F --> G[Support Pdf]
    F --> H[Site Web Internet]
</pre>

## Maintien en cohérence du CCT, contrôle et corrections
Le document est contrôlé et maintenu en cohérence par l'equipe d'Architecture d'Entreprise.

Si une erreur est décelée, un relecteur peut soumettre des demandes d'évolutions ou des corrections via l'ouverture d'un fil de discussion [Issue] publié sur le dépôt Git.


## La publication 
### Automatisation de la publication sur le site web Intranet

Le responsable de contenu est garant de ces fiches. Dès que celui-ci décide d'intégrer ses modifications complètes au travers d'un "pull request" de sa branche vers la branche "main", le système génére immédiatement une nouvelle version du site CCT intégrant les mises à jour publiées sur le site web Intranet. 

Ce contenu étant mis à disposition "en l'état", un contrôle de cohérence sera réalisé par les équipes d'Architecture d'Entreprise. 

Suite à leur validation, les contenus déjà disponibles sur le site Web Intranet seront estampilés "officiels" et dupliqués sur le site Web Internet.

Ce contenu est aussi rendu disponible au format PDF. 


{%include "components/back_to_top.njk" %}