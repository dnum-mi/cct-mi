---
title: Résumé opérationnel
layout: layouts/page_date_readtime.njk
showBreadcrumb: true
date: git Last Modified
eleventyNavigation:
  key: Executive summary
  parent: Présentation
  order: 1
---

# Préambule

À travers sa doctrine **Cloud au centre**, l’État encourage l’ensemble des acteurs publics à se saisir de son potentiel afin de développer une nouvelle génération de services numériques de qualité, tout en protégeant au mieux les données des entreprises et des citoyens français.

Dans le but de disposer un SI adapté et agile, le MIOM a posé un ensemble de normes techniques et des recommandations de nature, formalisés dans un document de Cadre de Cohérence Technique (CCT), pour le développement de nouvelles applications compatibles avec ces normes et hébergées sur son infrastructure, et de services de qualité qui répondent aux besoins des métiers et déployables rapidement et à coûts réduits.

Pour un accès rapide aux documents du CCT correspondant à votre besoin, vous pouvez vous référer au tableau ci-dessous :

{% from "components/component.njk" import component with context %}
{{ component("table", {
    title: "Interet des contenus du site",
    headers: ["","Env. numérique de travail (MIOM et Intermin)", "Legacy / Cloud Pi (MIOM)","Cloud Native (Intermin)","Guide de bonnes pratiques d'architecture (Intermin et MIOM)","Guide de bonnes pratiques de sécurité (Intermin et MIOM)"],
    data: [
      ["Env. numérique de travail uniquement","X","","","X","X"],
      ["Env. numérique de travail & Cloud Pi Native","X","","X","X","X"],
      ["Env. numérique de travail & Legacy/Cloud Pi","X","X","","X","X"],
      ["Cloud Pi Native *uniquement*","","","X","X","X"],
      ["Legacy/Cloud Pi *uniquement*","","X","","X","X"]
    ]
}) }}



{%include "components/back_to_top.njk" %}