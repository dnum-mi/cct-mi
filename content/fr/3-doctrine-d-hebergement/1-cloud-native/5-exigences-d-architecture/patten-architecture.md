---
title: Patterns d'architecture
layout: layouts/page_date_readtime.njk
showBreadcrumb: true
date: Last Modified
---

La partie qui suit décrit des patterns d'architecture en cohérence avec l'approche Cloud Native : 


Voici une solution d'architecture applicative dans un environnement Kubernetes et décrite grâce à mermaid<SPACE>:

<pre class="mermaid">
 graph LR;
 client([client])-. Ingress-managed <br> load balancer .->ingress[Ingress];
 ingress-->|routing rule|cct-mi[service 'cct-mi'];
 subgraph cluster
 ingress;
 cct-mi-->pod1[Pod];
 cct-mi-->pod2[Pod];
 end
 classDef plain fill:#ddd,stroke:#fff,stroke-width:4px,color:#000;
 classDef k8s fill:#326ce5,stroke:#fff,stroke-width:4px,color:#fff;
 classDef cluster fill:#fff,stroke:#bbb,stroke-width:2px,color:#326ce5;
 class ingress,cct-mi,pod1,pod2 k8s;
 class client plain;
 class cluster cluster;
</pre>




{%include "components/back_to_top.njk" %}