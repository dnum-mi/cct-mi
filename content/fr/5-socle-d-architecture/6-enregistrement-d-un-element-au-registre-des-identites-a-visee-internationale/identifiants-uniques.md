---
title: Enregistrer un identifiant unique au registre international
layout: layouts/page_date_readtime.njk
showBreadcrumb: true
date: git Last Modified
eleventyNavigation:
  key: Enregistrer un identifiant unique au registre international
  parent: Socle architecture
  order: 6
---

# Référentiel d'identifiants uniques (OID, BIN / IIN, RID)

Le ministère de l'intérieur, comme tout organisme public ou privé, peut avoir besoin d'obtenir - ou d'acquérir - des identifiants uniques, dont l'unicité peut être garantie à un niveau national ou international. Le CCT ne traite ici que d'identifiants uniques techniques, nécessités par des activités telles que la gestion de ses infrastructures à clés publiques, son activité d'émetteur de carte à puce (passeport, CNIE, carte professionnelle ...etc).

Ces identifiants sont 
- l'Object IDentifier (**OID**) - Identification unique d'objet utilisée dans un grand nombre de protocoles
- et dans le domaine des cartes à puce
  - le numéro d'identification d'émetteur de carte : **BIN** ou **IIN**
  - le numéro d'identification de fournisseur d'application (hébergée sur une carte à puce) : **RID**


## Les OID
### <a name="Def">Qu'est qu'un OID ?</a>

Pour paraphraser la définition de [wikipedia](https://fr.wikipedia.org/wiki/OID), un OID, ou "Object Identifier", est un identifiant universel (c'est à dire unique à l'échelle de la planète) utilisé pour nommer un objet. Quel type d'objet peut on identifier ainsi ?

En fait tout type d'objet que l'on souhaite, à des fins d'interopérabilité, identifier de manière unique : ce peut être un attribut dans un schéma d'annuaire LDAP, une variable "MIB" utilisée pour administrer un équipement ou un logiciel à distance (avec le protocole SNMP), des codes pays, des codes BIC pour le domaine bancaire, ou dans le cadre d'une IGC (Infrastructure à clé publique), un type de certificat, une politique de certification  ..etc.

Au ministère de l'intérieur, les OID sont utilisés pour identifier des attributs dans nos schémas d'annuaire LDAP et notre Référentiel des Identités et des Organisations (RIO), pour les IGC et autres services de confiance notamment.

A l'origine les identifiants OID sont été définis par l'[UIT-T](http://www.itu.int/fr/about/Pages/default.aspx) dans le cadre du standard ASN.1, puis rapidement largement exploités par la communauté Internet dans le cadre du protocole de gestion de réseau SNMP.

L'OID est représenté sous la forme d'une suite de nombres entiers, et organisé hiérarchiquement de façon à permettre la délégation d'autorité d'attribution. Dans le principe, un OID est construit  de façon analogue à un nom de domaine DNS, et l'objectif est le même, à savoir se donner le moyen de nommer des objets (des domaines) de façon totalement décentralisée mais tout en garantissant leur unicité globale. L'unicité des identifiants est bien sûre vitale pour atteindre l'interopérabilité des logiciels.

Il est possible de consulter l'arbre des OID, dans sa partie la plus publique, en interrogeant l'[OID Repository](http://www.oid-info.com/). 

### Modalités d'obtention

Le SHFD est responsable de l'unicité, de la cohérence et de l'enregistrement des OID dans le périmètre du ministère de l'intérieur.

Vous voulez créer un nouvel OID : [Contact OID] *a définir*




## identifiant pour les cartes à puce

### Numéros d'identification pour les cartes à puce

De part ses métiers le ministère de l'intérieur est émetteur de cartes à puces et fournisseur d'applications hébergées dans ces cartes à puce. 

Il est en effet émetteur de titres sécurisés comme le passeport, la CNIE (prochainement), les cartes professionnelles de ses agents.
Il pourrait également être émetteur de cartes SIM au titre d'un rôle d'opérateur de réseau radio étatique (RRF).

Ces deux activités sont fortement normées et nécessitent l'obtention de numéros d'identification : 
- Numéro d'identification d'émetteur de carte : IIN (Issuer Identification  Number) ou BIN (Bank Identification Number)
- Numéro d'identification de fournisseur d'application : RID (Registered Application Provider Identifier)

Ces numéros d'identification peuvent être à portée nationale ou internationales. Ils sont régis par des normes qui en définissent très précisément la finalité, le format et le processus d'obtention.

#### Numéro d'identification d'émetteur de carte - BIN et IIN

L'organisme émetteur de carte d'identification (carte à puce) peut être identifié de façon unique par un numéro d'identification **BIN (Bank Identification Number)** ou **IIN (Issuer Identification Number)**. Dans les faits, les deux acronymes sont utilisés de façon interchangeable.

Le numéro d'identification d'émetteur de carte, IIN (Issuer Identification Number), est défini par la norme **ISO/IEC 7812-1:2017**. La norme a évolué en 2017, faisant passer l'IIN de six à huit chiffres.

Pour la France, l'AFNOR peut fournir et être garante de l'unicité de ces numéros BIN / IID.

#### Numéro d'identification de fournisseur d'application - AID et RID

Tel que le spécifie la norme **ISO/IEC 7816-5**, une application hébergée par une carte à puce est identifiée de façon unique par son AID (Application ID). Ce numéro d'indentification de l'application se décompose en deux parties : 
- le numéro d'identification, unique, du fournisseur de l'application - ou Registered Application Provider Identification Number (**RID**)
- un champs optionnel : Proprietary Application Identifier Extension (**PIX**), utilisé pour distinguer plusieurs applications du même fournisseur.

Pour la France, l'AFNOR peut fournir et être garante de l'unicité de ce numéro d'identification de fournisseur d'application RID.

### Modalités d'obtention

Les numéros d'identification BIN / IIN et RID sont obtenus et acquis auprès de l'AFNOR. Pour des raisons de maintien de l'historique, le SHDF prend en charge ces demandes : [Contact carte à puces] *a définir*






{% include "components/back_to_top.njk" %}