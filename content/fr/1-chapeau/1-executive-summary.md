---
title: Executive summary
layout: layouts/page.njk
showBreadcrumb: true
eleventyNavigation:
  key: Executive summary
  parent: À propos
  order: 1
---



# Executive summary

À travers sa doctrine « Cloud au centre », l’État encourage l’ensemble des acteurs publics à se saisir de son potentiel afin de développer une nouvelle génération de services numériques de qualité, tout en protégeant au mieux les données des entreprises et des citoyens français.

Dans le but de disposer un SI adapté et agile, le MIOM a posé un ensemble de normes techniques et des recommandations de nature, formalisés dans un document de Cadre de Cohérence Technique (CCT), pour le développement de nouvelles applications compatibles avec ces normes et hébergées sur son infrastructure, et de services de qualité qui répondent aux besoins des métiers et déployables rapidement et à coûts réduits.

Ce document représente le document « chapeau » du Cadre de Cohérence Technique (CCT) qui vise à faire le lien vers d’autres documents, selon les offres du MIOM et interministériel, dont chacun d’eux est couplé d’un guide de bonnes pratiques et d’une liste d’annexes et d’exigences.

Le premier chapitre de ce document décrit le contexte et les objectifs du CCT. Il donne une visibilité sur son architecture documentaire et son applicabilité selon différents cas d’usages, tout en mentionnant les domaines concernés et les acteurs ciblés ainsi que son utilisation au sein des projets et des processus du MIOM et interministériel. Le deuxième chapitre défini le cadre d’applicabilité de ce CCT sur les différentes offres de services avec les usages concernés et le dernier chapitre définit son cycle de vie et sa « gouvernance.

Pour un accès rapide aux documents du CCT correspondant à votre besoin, vous pouvez vous référer au tableau ci-dessous :

{% from "components/component.njk" import component with context %}
{{ component("table", {
    title: "Interet des contenus du site",
    headers: ["","Env. numérique de travail (MIOM et Intermin)", "Legacy / Cloud Pi (MIOM)","Cloud Native (Intermin)","Guide de bonnes pratiques d'archi (Intermin et MIOM)","Guide de bonnes pratiques de sécurité (Intermin et MIOM)"],
    data: [
      ["Env. numérique de travail *uniquement*","X","","","X","X"],
      ["Env. numérique de travail & Cloud Pi Native","X","","X","X","X"],
      ["Env. numérique de travail & Legacy/Cloud Pi","X","X","","X","X"],
      ["Cloud Pi Native *uniquement*","","","X","X","X"],
      ["Legacy/Cloud Pi *uniquement*","","X","","X","X"]
    ]
}) }}



{%include "components/back_to_top.njk" %}