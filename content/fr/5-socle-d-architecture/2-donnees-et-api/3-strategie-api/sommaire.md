---
title: Doctrine API
layout: layouts/page_date_readtime.njk
showBreadcrumb: true
date: git Last Modified
---

## Doctrine API

- [**Introduction**](../introduction/index.html#intro)
- [**Les API**](../introduction/index.html#API)
- [**Choix technologique**](../introduction/index.html#choix)


<div class="fr-grid-row fr-grid-row--gutters fr-mb-1w">
    <div class="fr-col-md-6 fr-col">
                {% from "components/component.njk" import component with context %}
                <div>
                    {{ component("card", {
                        url: "/5-socle-d-architecture/2-donnees-et-api/3-strategie-api/principes",
                        title: "Les principes",
                        description: "Une API doit exposer des services métiers",
                        tags: ["api"],
                        date: "2023-06-21" | jsDateObject,
                        badges: [],
                        image: {
                            path: "../../../../../public/img/undraw_Services_re_hu5n.png",
                            alt: "principes"
                        },
                        orientation: horizontal
                    }) }}
                </div>
    </div>
    <div class="fr-col-md-6 fr-col">
                {% from "components/component.njk" import component with context %}
                <div>
                    {{ component("card", {
                        url: "/5-socle-d-architecture/2-donnees-et-api/3-strategie-api/regles",
                        title: "Les règles",
                        description: "Les règles et précisions associées aux principes",
                        tags: ["api"],
                        date: "2023-06-21" | jsDateObject,
                        badges: [],
                        image: {
                            path: "../../../../../public/img/undraw_Terms_re_6ak4.png",
                            alt: "regles"
                        },
                        oriental: horizontal
                    }) }}
                </div>
    </div>
</div>


{% include "components/back_to_top.njk" %}
