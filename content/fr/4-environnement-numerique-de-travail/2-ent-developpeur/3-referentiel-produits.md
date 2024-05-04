---
title: referentiel des produits de l'ENT du developpeur
layout: layouts/page_date_readtime.njk
showBreadcrumb: true
date: git Last Modified
---

<hr>
<h2>
<a name="AT"> Partie 2 : Architecture Technique - [ AT ]</a>
</h2>
<p class="comm_italic">Pour les logiciels pris en charge au march&eacute; de support logiciels libres, il est indiqu&eacute; "Oui" dans la colonne "Supp. LL"</p>
<hr>
<h3>
<a name="ATMA"> Chapitre 1 : Mod&egrave;les d'architecture - [ MA ]</a>
</h3>
<p class="comm_italic"></p>
<h3>
<a name="ATLS"> Chapitre 2 : Logiciels Syst&egrave;mes - [ LS ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">AT-1368</td><td class="inc_open">CentOS</td><td class="inc_open">CentOS</td><td>6</td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Distribution utilis&eacute;e (tiers 2 ou tiers 3) en l'absence de n&eacute;cessit&eacute; de certification pour le projet. Non utilis&eacute; en s&eacute;curit&eacute; int&eacute;rieure.</td>
</tr>
<tr>
<td class="inc_open">AT-1410</td><td class="inc_open">CentOS</td><td class="inc_open">CentOS</td><td>7</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Distribution utilis&eacute;e (tiers 2 ou tiers 3) en l'absence de n&eacute;cessit&eacute; de certification pour le projet. <br/>Non utilis&eacute; en s&eacute;curit&eacute; int&eacute;rieure.</td>
</tr>
<tr>
<td class="inc_open">AT-1409</td><td class="inc_open">Debian GNU Linux</td><td class="inc_open">debian.org</td><td>Version &laquo;&nbsp;stable&nbsp;&raquo; de l&rsquo;&eacute;diteur</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. L&rsquo;&eacute;diteur recommande d&rsquo;utiliser pour la production sa distribution dite &laquo;&nbsp;stable&nbsp;&raquo;.  Le CCT s&rsquo;aligne sur cette recommandation. Les mises &agrave; jours de la distribution stable (num&eacute;ro de version mineur) se limitent &agrave; des correctifs de s&eacute;curit&eacute;. <br/>Le CCT conseille la migration des serveurs utilisant la distribution &laquo;&nbsp;Oldstable&nbsp;&raquo; (N-1).<br/>Cf https://www.debian.org/releases/index.fr.html</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1380</td><td class="inc_nonopen">UNIX AIX</td><td class="inc_nonopen">BULL</td><td></td><td class="statut_M">M</td><td></td><td class="comm_italic">DTNUM : Contexte d'emploi limit&eacute; au tiers 3</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1457</td><td class="inc_nonopen">Unix AIX</td><td class="inc_nonopen">BULL</td><td>7.2</td><td class="statut_R">R</td><td></td><td class="comm_italic">Usage restreint aux serveurs BULL Escala &agrave; base de processeurs Power8 dans un premier temps.</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1507</td><td class="inc_nonopen">UNIX Solaris</td><td class="inc_nonopen">Oracle</td><td>Solaris 11</td><td class="statut_A">A</td><td></td><td class="comm_italic">Contexte d'emploi limit&eacute; au tiers 3 (IPMS GN) et uniquement pour les bases de donn&eacute;es Oracle.</td>
</tr>
<tr>
<td class="inc_open">AT-1137</td><td class="inc_open">Red Hat Enterprise Linux</td><td class="inc_open">Red Hat</td><td>RHEL 5</td><td class="statut_A">A</td><td></td><td class="comm_italic">Hors p&eacute;rim&egrave;tre datacentres de la S&eacute;curit&eacute; Int&eacute;rieure.</td>
</tr>
<tr>
<td class="inc_open">AT-1364</td><td class="inc_open">Red Hat Enterprise Linux</td><td class="inc_open">Red Hat</td><td>RHEL 6</td><td class="statut_A">A</td><td></td><td class="comm_italic">Hors p&eacute;rim&egrave;tre datacentres de la S&eacute;curit&eacute; Int&eacute;rieure.</td>
</tr>
<tr>
<td class="inc_open">AT-1411</td><td class="inc_open">Red Hat Enterprise Linux</td><td class="inc_open">Red Hat</td><td>RHEL 7</td><td class="statut_A">A</td><td></td><td class="comm_italic">Hors p&eacute;rim&egrave;tre datacentres de la S&eacute;curit&eacute; Int&eacute;rieure.</td>
</tr>
<tr>
<td class="inc_open">AT-1508</td><td class="inc_open">SUSE Linux Enterprise Server</td><td class="inc_open">Suse.com</td><td>12 SP1</td><td class="statut_A">A</td><td></td><td class="comm_italic">P&eacute;rim&egrave;tre ST(SI)&sup2;, OS r&eacute;serv&eacute; pour les applications n&eacute;cessitant une distribution Linux support&eacute;e.</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1146</td><td class="inc_nonopen">Windows Server</td><td class="inc_nonopen">Microsoft</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic"></td>
</tr>
</tbody>
</table>
<h3>
<a name="ATT1"> Chapitre 3 : Tiers Pr&eacute;sentation - [ T1 ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">AT-1148</td><td class="inc_open">Apache</td><td class="inc_open">Apache Software Foundation</td><td>2.2</td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic"></td>
</tr>
<tr>
<td class="inc_open">AT-1412</td><td class="inc_open">Apache</td><td class="inc_open">Apache Software Foundation</td><td>2.4</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic"></td>
</tr>
<tr>
<td class="inc_open">AT-1379</td><td class="inc_open">Nginx</td><td class="inc_open">nginx.org</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Version native de la distribution concern&eacute;e.<br/>Frontal web pour des cas d'usage limitatifs :<br/>- ST(SI)&sup2; : serveur web &agrave; forte charge ponctuelle<br/>- DTNUM : reverse proxy pour sites ouverts sur Internet</td>
</tr>
</tbody>
</table>
<h3>
<a name="ATT2"> Chapitre 4 : Tiers application/m&eacute;tier - [ T2 ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">AT-1484</td><td class="inc_open">Tomcat</td><td class="inc_open">Apache Software Foundation</td><td>7</td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Serveur d'application Java EE, conteneur de servlet. La version 4 de tomcat supporte les versions de java &gt;=6. La version native de la distribution est &agrave; privil&eacute;gier.</td>
</tr>
<tr>
<td class="inc_open">AT-1485</td><td class="inc_open">Tomcat</td><td class="inc_open">Apache Software Foundation</td><td>8</td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Serveur d'application JavaEE, conteneur de servlet. Version incluse &agrave; la version 9 de la distribution Debian.</td>
</tr>
<tr>
<td class="inc_open">AT-1486</td><td class="inc_open">Tomcat</td><td class="inc_open">Apache Software Foundation</td><td>9 &ndash; Version SILL</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Serveur d'application JavaEE, conteneur de servlet. Version incluse &agrave; la version 9 de la distribution Debian. Supporte Java 8 ou plus.</td>
</tr>
<tr>
<td class="inc_open">AT-1448</td><td class="inc_open">Wildfly (Jboss AS)</td><td class="inc_open">RedHat</td><td></td><td class="statut_A">A</td><td>Oui</td><td class="comm_italic">Wildfly (anciennement Jboss AS (Application Server)) est la version communautaire de Jboss EAP (Enterprise Application Platform). C&rsquo;est un framework Java EE complet qui peut &ecirc;tre utilis&eacute;, sur autorisation, par exemple pour des parties de la sp&eacute;cification java EE non couverte par Tomcat.</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1424</td><td class="inc_nonopen">Weblogic</td><td class="inc_nonopen">Oracle</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Serveur d'application java EE et java SE</td>
</tr>
<tr>
<td class="inc_open">AT-1447</td><td class="inc_open">JOnAS</td><td class="inc_open">OW2</td><td>5</td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic"></td>
</tr>
<tr>
<td class="inc_open">AT-1156</td><td class="inc_open">Jetty</td><td class="inc_open">Fondation Eclipse</td><td></td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Serveur HTTP et moteur de servlet java</td>
</tr>
<tr>
<td class="inc_open">AT-1339</td><td class="inc_open">CXF</td><td class="inc_open">Apache Software Foundation</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Framework java de d&eacute;veloppement de services WEB. A utiliser pour les Webservices SOAP (inter-applicatif)</td>
</tr>
<tr>
<td class="inc_open">AT-1338</td><td class="inc_open">mod_proxy</td><td class="inc_open">Apache software Foundation</td><td></td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Serveur mandataire - passerelle multi-protocoleUtilisation de la version nativement incluse dans la distribution linux concern&eacute;e.</td>
</tr>
<tr>
<td class="inc_open">AT-1159</td><td class="inc_open">Axis 2</td><td class="inc_open">Apache Software Foundation</td><td>1.x</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Framework de d&eacute;veloppement de service web. A utiliser pour les services web SOAP (inter-applicatifs)</td>
</tr>
<tr>
<td class="inc_open">AT-1153</td><td class="inc_open">mod_jk (connecteur AJP13)</td><td class="inc_open">Apache Software Foundation</td><td></td><td class="statut_A">A</td><td>Oui</td><td class="comm_italic">
Mod_jk est un module Apache qui g&egrave;re la communication et la r&eacute;partition de charge entre les serveurs Apache et Tomcat. Utilisation sur d&eacute;rogation. Le projet devra fournir le composant et ses d&eacute;pendances au format "rpm" s'il doit &ecirc;tre install&eacute; sur CentOS ou RedHat. Si la d&eacute;rogation porte sur une distribution Debian, utiliser le paquet nativement disponible sous cette distribution.</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1423</td><td class="inc_nonopen">Tuxedo</td><td class="inc_nonopen">Oracle</td><td>12c</td><td class="statut_A">A</td><td></td><td class="comm_italic">Serveur transactionnel. Transaction for UniX, Extended for Distributed Operation.</td>
</tr>
<tr>
<td class="inc_open">AT-1434</td><td class="inc_open">PHP FPM</td><td class="inc_open"></td><td>Version distrib</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. P&eacute;rim&egrave;tre restreint au ST(SI)&sup2;. Version de la distribution.Module d'interface SAPI pour l'int&eacute;gration de PHP sur un serveur web</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1435</td><td class="inc_nonopen">Zend Server</td><td class="inc_nonopen">Zend</td><td>5</td><td class="statut_M">M</td><td></td><td class="comm_italic">P&eacute;rim&egrave;tre restreint au ST(SI)&sup2;</td>
</tr>
<tr>
<td class="inc_open">AT-1453</td><td class="inc_open">Node.js</td><td class="inc_open">Nodejs.org</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL.Serveur d'application et serveur web en javascript, reposant sur la machine virtuelle javascript V8.</td>
</tr>
<tr>
<td class="inc_open">AT-1555</td><td class="inc_open">Npm</td><td class="inc_open">Nodejs.org</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Gestionnaire de paquet pour Node.JS</td>
</tr>
</tbody>
</table>
<h3>
<a name="ATIN"> Chapitre 5 : Intergiciel - [ IN ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">AT-1384</td><td class="inc_open">TIS (Talend Int&eacute;gration Suite)</td><td class="inc_open">Talend</td><td>8.x</td><td class="statut_A">A</td><td></td><td class="comm_italic">Edition Entreprise soumise &agrave; licence<br/>Int&eacute;gration de donn&eacute;es.</td>
</tr>
<tr>
<td class="inc_open">AT-1385</td><td class="inc_open">TOS (Talend Open Studio)</td><td class="inc_open">Talend</td><td>8.x</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Version mono-utilisateur pour l'int&eacute;gration de donn&eacute;es.<br/>Pour des flux de donn&eacute;es limit&eacute;s.</td>
</tr>
<tr>
<td class="inc_open">AT-1514</td><td class="inc_open">Talend Data Integration (ETL)</td><td class="inc_open">Talend</td><td>8.x</td><td class="statut_A">A</td><td></td><td class="comm_italic">Version soumise &agrave; souscription. Version communautaire&nbsp;: Talend Open Studio for Data Integration</td>
</tr>
<tr>
<td class="inc_open">AT-1516</td><td class="inc_open">Talend Application Integration (ESB)</td><td class="inc_open">Talend</td><td>8.x</td><td class="statut_A">A</td><td></td><td class="comm_italic">Version soumise &agrave; souscription. Version communautaire&nbsp;: Talend Open Studio for ESB</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1305</td><td class="inc_nonopen">Axway Transfer CFT</td><td class="inc_nonopen">AXWAY</td><td>3</td><td class="statut_A">A</td><td></td><td class="comm_italic">Transfert de fichiers</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1249</td><td class="inc_nonopen">TM1</td><td class="inc_nonopen">IBM</td><td></td><td class="statut_M">M</td><td></td><td class="comm_italic">
D&eacute;claration d&rsquo;activit&eacute;. Outil d&eacute;cisionnel (p&eacute;rim&egrave;tre Pr&eacute;fecture de Police)</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1000</td><td class="inc_nonopen">Bus de service TIBCO</td><td class="inc_nonopen">TiBCO Software</td><td>6.x</td><td class="statut_A">A</td><td></td><td class="comm_italic">Int&eacute;gration d'application via une fonction de bus de service (ESB). Les produits TIBCO sont mis en œuvre dans l&rsquo;offre de service INES, ainsi que la plate forme en cours de retrait SE DSIC.</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1014</td><td class="inc_nonopen">Axway Gateway</td><td class="inc_nonopen">AXWAY</td><td>6</td><td class="statut_A">A</td><td></td><td class="comm_italic">Transfert de fichiers multi protocoles. Produit mis en œuvre dans l&rsquo;offre de service INES dans la brique SAS.</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1529</td><td class="inc_nonopen">Axway API Gateway</td><td class="inc_nonopen">AXWAY</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Produit d&rsquo;API management, int&eacute;gr&eacute; &agrave; la plateforme d&rsquo;&eacute;change INES</td>
</tr>
</tbody>
</table>
<h3>
<a name="ATT3"> Chapitre 6 : Tiers Donn&eacute;es - [ T3 ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">AT-1541</td><td class="inc_open">PostgreSQL</td><td class="inc_open">PostgreSQL.org</td><td></td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Crit&egrave;re de choix de la version&nbsp;: <br/>- version par d&eacute;faut de la version de l&rsquo;OS (exemple, PostGreSQL v11 pour debian v10)<br/>- politique de l&rsquo;&eacute;diteur&nbsp;:  https://www.postgresql.org/support/versioning/<br/>Pr&eacute;f&eacute;rer les offres de service interne&nbsp;: notamment offre PostGreSQL-HA (r&eacute;siliente) de la DTNUM pour le cloud PI, bas&eacute;e sur PgPoolLa documentation MI associ&eacute;e se trouve sur le git&nbsp;: https://gitlab.forge-dc.cloudmi.minint.fr/communautes/bdd/sgbd-postgresql-ha
</td>
</tr>
<tr>
<td class="inc_open">AT-1358</td><td class="inc_open">Pgpool</td><td class="inc_open">pgpool.net</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Fournit des services de pooling de connexion,  de r&eacute;partition de charge sur plusieurs serveurs postgreSQL de type Master/Slave, de gestion de la haute disponibilit&eacute; de postgreSQL, de recovery (reconstruction automatique d&rsquo;un nœud postgreSQL apr&egrave;s un crash), de supervision de postgreSQL. <br/>Pr&eacute;f&eacute;rer les offres de service interne : notamment offre PostGreSQL-HA (r&eacute;siliente) de la DTNUM pour le cloud PI.</td>
</tr>
<tr>
<td class="inc_open">AT-1536</td><td class="inc_open">SQLite</td><td class="inc_open">SQLite.org</td><td>3.x</td><td class="statut_R">R</td><td></td><td class="comm_italic">Base de donn&eacute;e embarqu&eacute;e&nbsp;: biblioth&egrave;que &eacute;crite en C proposant un moteur de base de donn&eacute;es relationnelle accessible en langage SQL.</td>
</tr>
<tr>
<td class="inc_open">AT-1413</td><td class="inc_open">MariaDB</td><td class="inc_open">MariaDB Foundation</td><td>Version SILL</td><td class="statut_A">A</td><td></td><td class="comm_italic">Inscrit au SILL. </td>
</tr>
<tr>
<td class="inc_open">AT-1472</td><td class="inc_open">MySQL</td><td class="inc_open">Oracle</td><td>&lt;5.5</td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic">Privil&eacute;gier l&rsquo;usage de PostgreSQL ou &agrave; d&eacute;faut MariaDB</td>
</tr>
<tr>
<td class="inc_open">AT-1473</td><td class="inc_open">MySQL</td><td class="inc_open">Oracle</td><td>&gt;5.5</td><td class="statut_A">A</td><td>Oui</td><td class="comm_italic">Privil&eacute;gier l&rsquo;usage de PostgreSQL ou &agrave; d&eacute;faut MariaDB</td>
</tr>
<tr>
<td class="inc_open">AT-1502</td><td class="inc_open">PostGIS</td><td class="inc_open">Postgis.org</td><td>Version SILL</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Module spatial pour PostgreSQL</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1475</td><td class="inc_nonopen">Oracle</td><td class="inc_nonopen">Oracle</td><td>&lt;12</td><td class="statut_M">M</td><td></td><td class="comm_italic"></td>
</tr>
<tr>
<td class="inc_nonopen">AT-1474</td><td class="inc_nonopen">Oracle</td><td class="inc_nonopen">Oracle</td><td>12</td><td class="statut_A">A</td><td></td><td class="comm_italic"></td>
</tr>
<tr>
<td class="inc_open">AT-1505</td><td class="inc_open">MongoDB</td><td class="inc_open">MongoDB.com</td><td>Version SILL </td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Base de la famille NoSQL. Syst&egrave;me de gestion de base de donn&eacute;e orient&eacute;e document et ais&eacute;ment parall&eacute;lisable.</td>
</tr>
<tr>
<td class="inc_open">AT-1532</td><td class="inc_open">Redis</td><td class="inc_open">RedisLabs.com</td><td></td><td class="statut_A">A</td><td>Non</td><td class="comm_italic">Base de la famille NoSQL. InMemory (toutes les donn&eacute;es sont stock&eacute;e en RAM). syst&egrave;me de gestion de base de donn&eacute;es clef-valeur scalable. Fonction de broker de message.</td>
</tr>
<tr>
<td class="inc_open">AT-1534</td><td class="inc_open">Cassandra</td><td class="inc_open">Cassandra.apache.org</td><td></td><td class="statut_A">A</td><td>Non</td><td class="comm_italic">Base de la famille NoSQL, con&ccedil;ue pour g&eacute;rer des quantit&eacute;s massives de donn&eacute;es sur un grand nombre de serveurs. Usage restreint au ST(SI)&sup2;</td>
</tr>
<tr>
<td class="inc_open">AT-1535</td><td class="inc_open">OrientDB</td><td class="inc_open">OrientDB.com</td><td></td><td class="statut_A">A</td><td>Non</td><td class="comm_italic">Base de la famille NoSQL, multi-mod&egrave;le&nbsp;: graphe, document, cl&eacute;/valeur, objet. Usage restreint au ST(SI)&sup2;</td>
</tr>
<tr>
<td class="inc_nonopen">AT-1548</td><td class="inc_nonopen">Vertica</td><td class="inc_nonopen">HPE (Hewlett Packard Enterprise)</td><td></td><td class="statut_A">A</td><td>Non</td><td class="comm_italic">Base de donn&eacute;e analytique, orient&eacute;e colonne. Datamining sur donn&eacute;es de masse (100 millions &agrave; 1 milliard).</td>
</tr>
</tbody>
</table>
<h3>
<a name="ATT0"> Chapitre 7 : Client WEB (pr&eacute;sentation et donn&eacute;es) - [ T0 ]</a>
</h3>
<p class="comm_italic">Les produits list&eacute;s dans ce chapitre d&eacute;notent l&rsquo;&eacute;volution des technologies et de l&rsquo;&eacute;tat de l&rsquo;art vers un r&eacute;enrichissement de la couche client. Avec en particulier toutes les possibilit&eacute;s offertes HTML 5, CSS 3 et javascript. La conception adaptative des interfaces (&laquo;&nbsp;responsive design) est obligatoire.</p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">AT-1441</td><td class="inc_open">Bootstrap</td><td class="inc_open">Twitter</td><td>4</td><td class="statut_R">R</td><td></td><td class="comm_italic">Framework d'interface HTML/CSS/javascript.</td>
</tr>
<tr>
<td class="inc_open">AT-1444</td><td class="inc_open">Leaflet</td><td class="inc_open">leafletjs.com</td><td>I.x</td><td class="statut_R">R</td><td></td><td class="comm_italic">Biblioth&egrave;que javascript pour cartes interactives. Recommand&eacute;e pour la pr&eacute;sentation de cartes, notamment dans les applications mobiles.</td>
</tr>
<tr>
<td class="inc_open">AT-1438</td><td class="inc_open">AngularJS</td><td class="inc_open">Google</td><td>1.4</td><td class="statut_R">R</td><td></td><td class="comm_italic">Biblioth&egrave;que Javascript</td>
</tr>
<tr>
<td class="inc_open">AT-1439</td><td class="inc_open">AngularJS</td><td class="inc_open">Google</td><td>8</td><td class="statut_A">A</td><td></td><td class="comm_italic">AngularJS V2 &eacute;tant une compl&egrave;te r&eacute;&eacute;criture par rapport &agrave; la premi&egrave;re version, le ST(SI)&sup2; a d&eacute;cid&eacute; de le remplacer par la biblioth&egrave;que ReactJS.</td>
</tr>
<tr>
<td class="inc_open">AT-1537</td><td class="inc_open">ReactJS</td><td class="inc_open">Facebook</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Biblioth&egrave;que Javascript &ndash; Alternative &agrave; AngularJS V2</td>
</tr>
<tr>
<td class="inc_open">AT-1544</td><td class="inc_open">Redux</td><td class="inc_open">Redux.js.org</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Conteneur d&rsquo;&eacute;tat pour les applications javascript &ndash; Souvent utilis&eacute; en association avec ReactJS.</td>
</tr>
<tr>
<td class="inc_open">AT-1550</td><td class="inc_open">VueJS</td><td class="inc_open">VueJS.org</td><td></td><td class="statut_R">R</td><td>Non</td><td class="comm_italic">Biblioth&egrave;que Javascript &ndash; Alternative &agrave; AngularJS et ReactJS</td>
</tr>
<tr>
<td class="inc_open">AT-1442</td><td class="inc_open">OpenLayers</td><td class="inc_open">OpenLayers.org</td><td>2.13</td><td class="statut_M">M</td><td></td><td class="comm_italic">Bilioth&egrave;que javascript pour les applications cartographiques.</td>
</tr>
<tr>
<td class="inc_open">AT-1443</td><td class="inc_open">OpenLayers</td><td class="inc_open">OpenLayers.org</td><td>3</td><td class="statut_R">R</td><td></td><td class="comm_italic">Bilioth&egrave;que javascript pour les applications cartographiques.</td>
</tr>
<tr>
<td class="maj_open">AT-1361</td><td class="maj_open">JQuery</td><td class="maj_open">Jquery.com</td><td>1.X</td><td class="statut_M">M</td><td></td><td class="comm_italic">Framework/librairie Javascript. Licence MIT</td>
</tr>
<tr>
<td class="maj_open">AT-1440</td><td class="maj_open">Jquery</td><td class="maj_open">Jquery.com</td><td>2.X</td><td class="statut_M">M</td><td></td><td class="comm_italic">Framework/librairie Javascript. Licence MIT</td>
</tr>
<tr>
<td class="inc_open">AT-1611</td><td class="inc_open">Jquery</td><td class="inc_open">Jquery.com</td><td>3.X</td><td class="statut_R">R</td><td></td><td class="comm_italic">Framework/librairie Javascript. Licence MIT</td>
</tr>
</tbody>
</table>
<hr>











<h2>
<a name="DV"> Partie 6 : D&eacute;veloppements - [ DV ]</a>
</h2>
<p class="comm_italic">Pour les logiciels pris en charge au march&eacute; de support logiciels libres, il est indiqu&eacute; "Oui" dans la colonne "Supp. LL"</p>
<hr>
<h3>
<a name="DVCO"> Chapitre 1 : Conception - [ CO ]</a>
</h3>
<p class="comm_italic"></p>
<h3>
<a name="DVRE"> Chapitre 2 : R&eacute;alisation - [ RE ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">DV-1477</td><td class="inc_open">Oracle OpenJDK</td><td class="inc_open">Oracle</td><td>7</td><td class="statut_M">M</td><td></td><td class="comm_italic">Version open source obsol&egrave;te du standard Java SE, tel que d&eacute;fini par le Java Community Process.</td>
</tr>
<tr>
<td class="inc_open">DV-1476</td><td class="inc_open">Oracle OpenJDK</td><td class="inc_open">Oracle</td><td>8</td><td class="statut_M">M</td><td></td><td class="comm_italic">Version open source du standard Java SE, tel que d&eacute;fini par le Java Community Process. Derni&egrave;re version supportant les applets et Java Web Start (JWS).</td>
</tr>
<tr>
<td class="inc_open">DV-1554</td><td class="inc_open">Oracle OpenJDK</td><td class="inc_open">Oracle</td><td>11</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit et recommand&eacute; au SILL. Version open source du standard Java SE, tel que d&eacute;fini par le Java Community Process. La version 11 est une version LTS (Long Term Support). Java Web start n&rsquo;est plus support&eacute; dans cette version. Chaque application doit embarquer son Java runtime d&eacute;di&eacute;.</td>
</tr>
<tr>
<td class="inc_nonopen">DV-1479</td><td class="inc_nonopen">Oracle JDK</td><td class="inc_nonopen">Oracle</td><td>7</td><td class="statut_M">M</td><td></td><td class="comm_italic">Java SE Development Kit &ndash; Pr&eacute;f&eacute;rer OpenJDK si un support &eacute;diteur n&rsquo;est pas n&eacute;cessaire</td>
</tr>
<tr>
<td class="inc_nonopen">DV-1478</td><td class="inc_nonopen">Oracle JDK</td><td class="inc_nonopen">Oracle</td><td>8</td><td class="statut_A">A</td><td></td><td class="comm_italic">Java SE Development Kit &ndash; Pr&eacute;f&eacute;rer OpenJDK si un support &eacute;diteur n&rsquo;est pas n&eacute;cessaire</td>
</tr>
<tr>
<td class="inc_nonopen">DV-1553</td><td class="inc_nonopen">Oracle JDK</td><td class="inc_nonopen">Oracle</td><td>11</td><td class="statut_A">A</td><td></td><td class="comm_italic">Java SE Development Kit &ndash; Pr&eacute;f&eacute;rer OpenJDK si un support &eacute;diteur n&rsquo;est pas n&eacute;cessaire</td>
</tr>
<tr>
<td class="inc_open">DV-1464</td><td class="inc_open">Android Studio</td><td class="inc_open">Google</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">D&eacute;veloppement natif d'application mobile.</td>
</tr>
<tr>
<td class="inc_open">DV-1460</td><td class="inc_open">Apache Cordova</td><td class="inc_open">Apache</td><td>19</td><td class="statut_R">R</td><td></td><td class="comm_italic">Pour le d&eacute;veloppement d'application hybrides. Code HTML / CSS / javascript peu adh&eacute;rent &agrave; l'OS.</td>
</tr>
<tr>
<td class="inc_open">DV-1459</td><td class="inc_open">SDK Android</td><td class="inc_open">Google</td><td>19</td><td class="statut_R">R</td><td></td><td class="comm_italic">Pour KitKat (4.4)</td>
</tr>
<tr>
<td class="inc_open">DV-1471</td><td class="inc_open">Git</td><td class="inc_open">git-scm.com</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Syst&egrave;me de gestion de versions d&eacute;centralis&eacute;, cr&eacute;&eacute; par Linus Torvalds. Pour les nouveaux projets, Git est pr&eacute;f&eacute;r&eacute; &agrave; SVN (Subversion).</td>
</tr>
<tr>
<td class="inc_open">DV-1538</td><td class="inc_open">Gitlab CE</td><td class="inc_open">GitLab Inc. </td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Forge permettant de g&eacute;rer des d&eacute;pots git</td>
</tr>
<tr>
<td class="inc_open">DV-1181</td><td class="inc_open">SubVersion</td><td class="inc_open">Apache software Foundation</td><td></td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Apache Subversion(ou svn) est un syst&egrave;me de gestion de version. Utiliser la version de la distribution Linux. Privil&eacute;gier GIT (qui poss&egrave;de une passerelle vers subversion).</td>
</tr>
<tr>
<td class="inc_open">DV-1182</td><td class="inc_open">Client Subversion - Tortoise</td><td class="inc_open">tortoisesvn.net
</td><td></td><td class="statut_M">M</td><td></td><td class="comm_italic">Gestion de versions.</td>
</tr>
<tr>
<td class="inc_open">DV-1375</td><td class="inc_open">Eclipse</td><td class="inc_open">eclipse.org</td><td>3.5 et +</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Environnement de d&eacute;veloppement</td>
</tr>
<tr>
<td class="inc_open">DV-1404</td><td class="inc_open">Zend studio for Eclipse</td><td class="inc_open">Zend Technologies</td><td>6.1</td><td class="statut_R">R</td><td></td><td class="comm_italic">Environnement de d&eacute;veloppement PHP</td>
</tr>
<tr>
<td class="inc_open">DV-1542</td><td class="inc_open">Symfony</td><td class="inc_open">SensioLabs</td><td>3</td><td class="statut_M">M</td><td></td><td class="comm_italic">Environnement de d&eacute;veloppement PHP. Version 3.4 en Long Term Support, jusqu&rsquo;&agrave; 2020</td>
</tr>
<tr>
<td class="inc_open">DV-1565</td><td class="inc_open">Symfony</td><td class="inc_open">SensioLabs</td><td>4.4 LTS</td><td class="statut_R">R</td><td></td><td class="comm_italic">Environnement de d&eacute;veloppement PHP. Version 4.4 en Long Term Support. Fin des corrections de bug en novembre 2022, fin des corrections de s&eacute;curit&eacute; en novembre 2023.</td>
</tr>
<tr>
<td class="inc_open">DV-1183</td><td class="inc_open">PgAdmin</td><td class="inc_open">Pgadmin.org</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Outil graphique de gestion de base de donn&eacute;es PostgreSQL.</td>
</tr>
<tr>
<td class="inc_open">DV-1106</td><td class="inc_open">Hibernate</td><td class="inc_open">Hibernate</td><td>4</td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic">Framework java g&eacute;rant la persistance des objets en base de donn&eacute;es relationnelle. La version 4 n&rsquo;est pas compatible avec la version LTS de java JDK 11.</td>
</tr>
<tr>
<td class="inc_open">DV-1437</td><td class="inc_open">Jersey</td><td class="inc_open">Oracle</td><td>2.13</td><td class="statut_R">R</td><td></td><td class="comm_italic">P&eacute;rim&egrave;tre restreint au ST(SI)&sup2;. <br/>Framework de d&eacute;veloppement de web services REST suivant les sp&eacute;cifications JAX-RS.</td>
</tr>
<tr>
<td class="inc_open">DV-1563</td><td class="inc_open">Hibernate</td><td class="inc_open">Hibernate.org</td><td>5.4</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Framework java g&eacute;rant la persistance des objets en base de donn&eacute;es relationnelle. La version stable 5.4 supporte java JDK 8 et 11 (version Long Term Support)</td>
</tr>
<tr>
<td class="inc_open">DV-1482</td><td class="inc_open">Spring</td><td class="inc_open">Pivotal Software</td><td>4</td><td class="statut_M">M</td><td></td><td class="comm_italic">Framework de d&eacute;veloppement d&rsquo;application web Java EE (Java Enterprise Edition)</td>
</tr>
<tr>
<td class="inc_open">DV-1562</td><td class="inc_open">Spring</td><td class="inc_open">Vmware</td><td>&ge; 5.1</td><td class="statut_R">R</td><td></td><td class="comm_italic">Framework de d&eacute;veloppement d&rsquo;application web Java EE (Java Enterprise Edition). Java LTS 11 est support&eacute;e &agrave; partir de la version 5.1 de SPRING.</td>
</tr>
<tr>
<td class="inc_open">DV-1109</td><td class="inc_open">Struts 2</td><td class="inc_open">Apache Software Foundation</td><td>2.3.x</td><td class="statut_M">M</td><td></td><td class="comm_italic">Framework pour le d&eacute;veloppement d'applications Web J2EE (Java).</td>
</tr>
<tr>
<td class="inc_open">DV-1564</td><td class="inc_open">Struts 2</td><td class="inc_open">Apache Software Foundation</td><td>&gt;2.5.20</td><td class="statut_R">R</td><td></td><td class="comm_italic">Framework pour le d&eacute;veloppement d'applications Web J2EE (Java). Support de java 11 &agrave; partir de la version 2.5.20</td>
</tr>
<tr>
<td class="new_open">DV-1599</td><td class="new_open">Temurin</td><td class="new_open">Adoptium Working Group</td><td>Version LTS </td><td class="statut_R">R</td><td></td><td class="comm_italic">Java runtime</td>
</tr>
<tr>
<td class="inc_open">DV-1169</td><td class="inc_open">JSP (JavaServer Pages)
</td><td class="inc_open">Oracle</td><td>2.0</td><td class="statut_R">R</td><td></td><td class="comm_italic">Technique java pour g&eacute;n&eacute;ration de pages web.</td>
</tr>
<tr>
<td class="inc_open">DV-1170</td><td class="inc_open">JSP (JavaServer Pages)
</td><td class="inc_open">Oracle</td><td>2.1</td><td class="statut_R">R</td><td></td><td class="comm_italic">Technique java pour g&eacute;n&eacute;ration de pages web.</td>
</tr>
<tr>
<td class="inc_open">DV-1465</td><td class="inc_open">PHP Composer</td><td class="inc_open">getcomposer.org</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">P&eacute;rim&egrave;tre restreint au ST(SI)&sup2;. Gestion des d&eacute;pendances pour PHP (t&eacute;l&eacute;chargement des librairies requises), en interface avec un d&eacute;p&ocirc;t Git.</td>
</tr>
<tr>
<td class="inc_open">DV-1134</td><td class="inc_open">NUSOAP</td><td class="inc_open">NuSphere Corporation</td><td></td><td class="statut_M">M</td><td></td><td class="comm_italic">Librairie PHP pour cr&eacute;ation de web services SOAP. Les composants SOAP natifs de PHP (&agrave; partir de la 5.3) sont &agrave; privil&eacute;gier.</td>
</tr>
<tr>
<td class="inc_open">DV-1256</td><td class="inc_open">Maven</td><td class="inc_open">Apache Software Foundation</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Int&eacute;gration continue, gestion et automatisation de production des projets logiciels Java</td>
</tr>
<tr>
<td class="inc_open">DV-1462</td><td class="inc_open">Redmine</td><td class="inc_open">redmine.org</td><td>Version SILL</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Gestion de projet collaborative</td>
</tr>
<tr>
<td class="inc_open">DV-1180</td><td class="inc_open">MantisBT
</td><td class="inc_open">mantisbt.org</td><td>Version SILL</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Bug tracker &ndash; Suivi de bugs.</td>
</tr>
<tr>
<td class="inc_open">DV-1107</td><td class="inc_open">NetBeans</td><td class="inc_open">Apache</td><td>6 et sup.</td><td class="statut_A">A</td><td></td><td class="comm_italic">Environnement de d&eacute;veloppement int&eacute;gr&eacute; (EDI)</td>
</tr>
<tr>
<td class="inc_open">DV-1355</td><td class="inc_open">Play Framework</td><td class="inc_open">playframework.com</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Framework de d&eacute;veloppement Java et scala.<br/>Licence Apache 2.<br/>Porteur du produit au minist&egrave;re : STSI&sup2;/SDAC.</td>
</tr>
<tr>
<td class="inc_nonopen">DV-1176</td><td class="inc_nonopen">Visual Studio</td><td class="inc_nonopen">Microsoft</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">IDE de Microsoft</td>
</tr>
<tr>
<td class="inc_nonopen">DV-1177</td><td class="inc_nonopen">Zend Studio</td><td class="inc_nonopen">Zend Technologies</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Environnement de d&eacute;veloppement pour PHP</td>
</tr>
<tr>
<td class="inc_nonopen">DV-1103</td><td class="inc_nonopen">DotNet</td><td class="inc_nonopen">Microsoft</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Environnement de d&eacute;veloppement Microsoft</td>
</tr>
<tr>
<td class="inc_open">DV-1369</td><td class="inc_open">Ext JS</td><td class="inc_open">Sencha inc.</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Framework Javascript.Licence GPLv3</td>
</tr>
<tr>
<td class="inc_open">DV-1362</td><td class="inc_open">YahooUI</td><td class="inc_open">Yahoo</td><td>3.5.x</td><td class="statut_A">A</td><td></td><td class="comm_italic">Framework/librairie Javascript. Licence BSD. Utilisation dans le p&eacute;rim&egrave;tre PP.</td>
</tr>
<tr>
<td class="inc_open">DV-1257</td><td class="inc_open">XAMPP</td><td class="inc_open">apachefriends.org</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Environnement d'ex&eacute;cution Apache-Mysql-Php pour Linux.L'utilisation de ce composant est limit&eacute;e aux contextes de d&eacute;veloppement locaux et n'est pas autoris&eacute;e pour l'h&eacute;bergement de sites web. Les versions utilis&eacute;es doivent tenir compte des versions PHP, Perl et MySQL r&eacute;f&eacute;renc&eacute;es dans les piles logicielles.</td>
</tr>
<tr>
<td class="inc_open">DV-1258</td><td class="inc_open">WAMP</td><td class="inc_open">wampserver.com</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Environnement d'ex&eacute;cution Apache-Mysql-Php pour Windows.L'utilisation de ce composant est limit&eacute;e aux contextes de d&eacute;veloppement locaux et n'est pas autoris&eacute;e pour l'h&eacute;bergement de sites web. Les versions utilis&eacute;es doivent tenir compte des versions PHP et MySQL r&eacute;f&eacute;renc&eacute;es dans les piles logicielles.</td>
</tr>
<tr>
<td class="inc_nonopen">DV-1450</td><td class="inc_nonopen">Zend framework</td><td class="inc_nonopen">Zend Technologies</td><td>1</td><td class="statut_M">M</td><td></td><td class="comm_italic">Framework de d&eacute;veloppement PHP</td>
</tr>
<tr>
<td class="inc_nonopen">DV-1449</td><td class="inc_nonopen">Zend framework</td><td class="inc_nonopen">Zend Technologies</td><td>2</td><td class="statut_A">A</td><td></td><td class="comm_italic">Framework de d&eacute;veloppement PHP</td>
</tr>
<tr>
<td class="inc_open">DV-1452</td><td class="inc_open">Doctrine</td><td class="inc_open">doctrine-project.org</td><td>2</td><td class="statut_R">R</td><td></td><td class="comm_italic">P&eacute;rim&egrave;tre restreint au ST(SI)&sup2;.Framework de d&eacute;veloppement pour la couche d'acc&egrave;s aux donn&eacute;es de type ORM (Mapping Objet Relationnel) int&eacute;gr&eacute; &agrave; Zend Framework 2 et Symfony 2 mais pouvant &ecirc;tre utilis&eacute; seul.</td>
</tr>
<tr>
<td class="inc_open">DV-1461</td><td class="inc_open">Ionic</td><td class="inc_open"></td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">D&eacute;veloppement d'applications hybrides.</td>
</tr>
<tr>
<td class="inc_open">DV-1543</td><td class="inc_open">PHP</td><td class="inc_open">PHP.net</td><td></td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Privil&eacute;gier la version de la distribution de l&rsquo;OS. Sinon la version support&eacute;e par le framework Symfony, ou la version &laquo;&nbsp;Current Stable&nbsp;&raquo; de PHP (php.net)</td>
</tr>
<tr>
<td class="inc_nonopen">DV-1093</td><td class="inc_nonopen">C#</td><td class="inc_nonopen">Microsoft</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Langage de d&eacute;veloppement.</td>
</tr>
<tr>
<td class="inc_nonopen">DV-1094</td><td class="inc_nonopen">C++</td><td class="inc_nonopen">Microsoft</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Langage de d&eacute;veloppement.</td>
</tr>
<tr>
<td class="inc_open">DV-1097</td><td class="inc_open">PERL</td><td class="inc_open">Perl.org</td><td></td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Langage de d&eacute;veloppement orient&eacute; scripts/reporting. Version native de la distribution Linux.</td>
</tr>
<tr>
<td class="inc_open">DV-1099</td><td class="inc_open">Python</td><td class="inc_open">python.org</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Langage de d&eacute;veloppement.</td>
</tr>
<tr>
<td class="inc_open">DV-1540</td><td class="inc_open">SCALA</td><td class="inc_open">scala-lang.org</td><td></td><td class="statut_O">O</td><td></td><td class="comm_italic">Langage de programmation multi-paradigme con&ccedil;u &agrave; l'&Eacute;cole polytechnique f&eacute;d&eacute;rale de Lausanne (EPFL).</td>
</tr>
<tr>
<td class="inc_open">DV-1545</td><td class="inc_open">EcmaScript (javascript)</td><td class="inc_open">ECMA</td><td>6</td><td class="statut_R">R</td><td></td><td class="comm_italic">Sp&eacute;cification ECMA du langage javascript</td>
</tr>
</tbody>
</table>
<h3>
<a name="DVEX"> Chapitre 3 : Exploitabilit&eacute; - [ EX ]</a>
</h3>
<p class="comm_italic"></p>
<h3>
<a name="DVTS"> Chapitre 4 : Tests - [ TS ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">DV-1539</td><td class="inc_open">Jasmine</td><td class="inc_open">Jasmine.github.io</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Framework de test javascript pour navigateur et node.js</td>
</tr>
<tr>
<td class="inc_open">DV-1466</td><td class="inc_open">JUnit</td><td class="inc_open">JUnit.org</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Junit est un framework de test unitaire pour le langage de programmation Java.</td>
</tr>
<tr>
<td class="inc_open">DV-1467</td><td class="inc_open">PHPUnit</td><td class="inc_open">PHPUnit.de</td><td>4</td><td class="statut_R">R</td><td></td><td class="comm_italic">PHPUnit est un framework open source de tests unitaires d&eacute;di&eacute; au langage de programmation PHP.</td>
</tr>
<tr>
<td class="inc_open">DV-1468</td><td class="inc_open">SonarQube</td><td class="inc_open">Sonarsource</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Outil d'analyse de la qualit&eacute; du code multi-langages. Utilise notamment des outils d'analyse tels que findbugs, checkstyle, PMD ...</td>
</tr>
<tr>
<td class="inc_open">DV-1186</td><td class="inc_open">Jmeter</td><td class="inc_open">Apache Software Foundation</td><td>Version SILL</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Jmeter permet la programmation de sc&eacute;narios de tests de mont&eacute;e en charge automatis&eacute;s des serveurs par injection de requ&ecirc;tes HTTP.</td>
</tr>
<tr>
<td class="inc_open">DV-1282</td><td class="inc_open">Selenium Server</td><td class="inc_open">seleniumhq.org</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Automatisation de tests fonctionnels.</td>
</tr>
<tr>
<td class="inc_open">DV-1299</td><td class="inc_open">soapUI</td><td class="inc_open">soapui.org</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Outil de test de Web Services (client Windows en version gratuite ou plugin eclipse)</td>
</tr>
<tr>
<td class="inc_open">DV-1049</td><td class="inc_open">JXPLORER</td><td class="inc_open">jxplorer.org</td><td>3.3</td><td class="statut_A">A</td><td></td><td class="comm_italic">Client &eacute;diteur / explorateur LDAP</td>
</tr>
<tr>
<td class="inc_nonopen">DV-1188</td><td class="inc_nonopen">QALOAD</td><td class="inc_nonopen">MicroFocus</td><td>5.9</td><td class="statut_A">A</td><td></td><td class="comm_italic">Tests de charge.</td>
</tr>
</tbody>
</table>
<h3>
<a name="DVDE"> Chapitre 5 : D&eacute;ploiement - [ DE ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">DV-1469</td><td class="inc_open">Jenkins</td><td class="inc_open">jenkins-ci.org</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Jenkins est un outil open source d'int&eacute;gration continue.</td>
</tr>
<tr>
<td class="inc_open">DV-1470</td><td class="inc_open">Nexus</td><td class="inc_open">Sonatype.org</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. P&eacute;rim&egrave;tre restreint au ST(SI)&sup2;. Nexus est un repository manager. La plateforme Nexus ST(SI)&sup2; permet de (1) mettre &agrave; disposition les d&eacute;pendances n&eacute;cessaires des projets sans acc&egrave;s &agrave; Internet (2) maitriser la gestion des projets de mani&egrave;re centralis&eacute;e et d'uniformiser les d&eacute;pendances entre les projets (3) archiver les logiciels sign&eacute;s produits par les projets.</td>
</tr>
</tbody>
</table>
<hr>








<hr>
<h2>
<a name="SG"> Partie 8 : Composants &amp; services g&eacute;n&eacute;riques - [ SG ]</a>
</h2>
<p class="comm_italic"></p>
<hr>
<h3>
<a name="SGDN"> Chapitre 1 : DNS - [ DN ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">SG-1265</td><td class="inc_open">Bind</td><td class="inc_open">Internet Systems Consortium</td><td>9</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">
BIND (Berkeley Internet Name Daemon) est l&rsquo;impl&eacute;mentation la plus r&eacute;pandue du service de nom DNS (Domain Name System). Bind est embarqu&eacute; dans toutes les distributions Linux. Version mineure en fonction de la distribution Linux concern&eacute;e.</td>
</tr>
</tbody>
</table>
<h3>
<a name="SGOC"> Chapitre 2 : Outils de communication - [ OC ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_nonopen">SG-1496</td><td class="inc_nonopen">Cryptosmart</td><td class="inc_nonopen">Ercom (Ercom.fr)</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Solution de t&eacute;l&eacute;phonie chiffr&eacute;e, qualifi&eacute;e par l&rsquo;ANSSI, et int&eacute;gr&eacute;e &agrave; l&rsquo;offre de service Hesperis-NG</td>
</tr>
<tr>
<td class="inc_open">SG-1308</td><td class="inc_open">Postfix</td><td class="inc_open">postfix.org</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Serveur de livraison de courrier.</td>
</tr>
<tr>
<td class="inc_open">SG-1374</td><td class="inc_open">Postfix</td><td class="inc_open">postfix.org</td><td>2.9</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Serveur de livraison de courrier.<br/>Version native de Debian 7</td>
</tr>
<tr>
<td class="inc_open">SG-1190</td><td class="inc_open">Cyrus-IMAP</td><td class="inc_open"></td><td>Version distrib</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Serveur de messagerie multiprotocole.</td>
</tr>
<tr>
<td class="inc_open">SG-1370</td><td class="inc_open">Icasso</td><td class="inc_open">Aliasource</td><td></td><td class="statut_M">M</td><td></td><td class="comm_italic">Personnalisation d'OBM (Linagora).</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1191</td><td class="inc_nonopen">Microsoft Exchange</td><td class="inc_nonopen">Microsoft</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Syst&egrave;me de messagerie de Microsoft.</td>
</tr>
<tr>
<td class="inc_open">SG-1345</td><td class="inc_open">OBM</td><td class="inc_open">obm.org</td><td></td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic">Solution de messagerie collaborative</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1266</td><td class="inc_nonopen">
Exchange ActiveSync (EAS)
</td><td class="inc_nonopen">Microsoft</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">EAS est un protocole propri&eacute;taire de synchronisation de mail, agendas, contacts, t&acirc;ches, con&ccedil;u &agrave; l&rsquo;origine pour les &eacute;changes entre outlook et un serveur Exchange. Standard de fait sur les &eacute;quipements mobiles. A la diff&eacute;rence d&rsquo;un standard IETF tel que calDAV ou cardDAV, EAS poss&egrave;de une fonction de &laquo;&nbsp;push&nbsp;&raquo;&nbsp;: le serveur a la possibilit&eacute; de notifier ses clients de tout &eacute;v&egrave;nement. Il existe des impl&eacute;mentations opensource d&rsquo;EAS, telles que Z-Push.</td>
</tr>
<tr>
<td class="inc_open">SG-1279</td><td class="inc_open">Roundcube</td><td class="inc_open">roundcube.net</td><td>Version SILL</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Client webmail libre utilisant AJAX.<br/>Webmail - p&eacute;rim&egrave;tre DTNUM</td>
</tr>
<tr>
<td class="new_open">SG-1586</td><td class="new_open">Lime Survey (service web)</td><td class="new_open">Limesurvey.org</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Outils de sondages (enqu&ecirc;te en ligne).  Des instances mise en ligne en interne MIOM  sont disponibles (ex: https://questionnaires-en-ligne.sgami-ouest.interieur.rie.gouv.fr/index.php/)</td>
</tr>
<tr>
<td class="inc_open">SG-1197</td><td class="inc_open">Sympa</td><td class="inc_open"></td><td></td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Gestion de liste de diffusion.</td>
</tr>
<tr>
<td class="inc_open">SG-1556</td><td class="inc_open">RocketChat</td><td class="inc_open">https://rocket.chat/</td><td>Version SILL</td><td class="statut_R">R</td><td>Non</td><td class="comm_italic">Outil de communication en &eacute;quipe (chat).</td>
</tr>
<tr>
<td class="new_nonopen">SG-1606</td><td class="new_nonopen">Tchap</td><td class="new_nonopen">Services interminist&eacute;riels</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">
Solution interminist&eacute;rielle de messagerie instantan&eacute;e. 

https://www.numerique.gouv.fr/outils-agents/tchap-messagerie-instantanee-etat/

</td>
</tr>
<tr>
<td class="new_nonopen">SG-1607</td><td class="new_nonopen">Osmose</td><td class="new_nonopen">Services interminist&eacute;riels</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">plateforme collaborative interminist&eacute;rielle. https://osmose.numerique.gouv.fr/. La solution existe, mais Resana est la solution pr&eacute;conis&eacute;e pour le m&ecirc;me usage. Son utilisation est donc assujettie a l'entit&eacute; organisationnelle.</td>
</tr>
<tr>
<td class="new_nonopen">SG-1605</td><td class="new_nonopen">Resana</td><td class="new_nonopen">Services interminist&eacute;riels</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">plateforme collaborative interminist&eacute;rielle. https://resana.numerique.gouv.fr
</td>
</tr>
<tr>
<td class="new_nonopen">SG-1610</td><td class="new_nonopen">Audio conf&eacute;rence de l'Etat</td><td class="new_nonopen">Services interminist&eacute;riels</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Solution interminist&eacute;rielle d&rsquo;audioconf&eacute;rence. https://audioconf.numerique.gouv.fr/
</td>
</tr>
<tr>
<td class="maj_nonopen">SG-1549</td><td class="maj_nonopen">ComU</td><td class="maj_nonopen">Cisco</td><td></td><td class="statut_R">R</td><td>Non</td><td class="comm_italic">Solution de Web conf&eacute;rence d&eacute;ploy&eacute;e par la DTNUM</td>
</tr>
<tr>
<td class="new_nonopen">SG-1608</td><td class="new_nonopen">Web conf&eacute;rence de l'Etat</td><td class="new_nonopen">Services interminist&eacute;riels</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Solution interminist&eacute;ielle de Web conf&eacute;rence.  https://webconf.numerique.gouv.fr/
</td>
</tr>
<tr>
<td class="new_nonopen">SG-1609</td><td class="new_nonopen">W&eacute;binaire de l'Etat</td><td class="new_nonopen">Services interminist&eacute;riels</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Solution interminist&eacute;rielle de Web inaire. https://webinaire.numerique.gouv.fr/
</td>
</tr>
<tr>
<td class="new_nonopen">SG-1604</td><td class="new_nonopen">Envol</td><td class="new_nonopen">Services interminist&eacute;riels</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Service de transfert de fichiers volumineux de la DTNUM. La solution est accessible via https://envol2.si.minint.fr/ ou au travers de la messagerie.</td>
</tr>
<tr>
<td class="new_nonopen">SG-1603</td><td class="new_nonopen">France Transfert</td><td class="new_nonopen">Services interminist&eacute;riels</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Service interminist&eacute;riel de transfert de fichiers volumineux. https://francetransfert.numerique.gouv.fr/  Le service est non DR. Utiliser Envol dans ce cas de figure.</td>
</tr>
</tbody>
</table>
<h3>
<a name="SGAN"> Chapitre 3 : Annuaire - [ AN ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">SG-1307</td><td class="inc_open">OpenLDAP</td><td class="inc_open">openldap.org</td><td>Version SILL</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Impl&eacute;mentation open-source de LDAP (Lightweight Directory Access Protocol)</td>
</tr>
<tr>
<td class="inc_open">SG-1357</td><td class="inc_open">Apache Directory Studio</td><td class="inc_open">directory.apache.org</td><td>1.5.x</td><td class="statut_R">R</td><td></td><td class="comm_italic">Administration LDAP bas&eacute;e sur Eclipse.Navigateur LDAP bas&eacute; sur le studio Eclipse.</td>
</tr>
<tr>
<td class="inc_open">SG-1274</td><td class="inc_open">phpLDAPadmin (PLA)
</td><td class="inc_open"></td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Client web d'administration LDAP. Derni&egrave;re version&nbsp;: 1.2.3, de 2012. Est ce un projet suivi&nbsp;?</td>
</tr>
</tbody>
</table>
<h3>
<a name="SGSC"> Chapitre 4 : SIG/Cartographie - [ SC ]</a>
</h3>
<p class="comm_italic">Les produits de SIG et cartographie ont &eacute;t&eacute; regroup&eacute;s selon la classification suivante:- serveurs cartographiques- outils desktop (y compris les API)- outils Web (y compris les APIs)Les extensions pour les SGBD sont r&eacute;f&eacute;renc&eacute;es dans le domaine Architecture Technique - Tiers 3 (AT/T3).</p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_nonopen">SG-1203</td><td class="inc_nonopen">ArcGis &ndash; Suite ESRI</td><td class="inc_nonopen">ESRI</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">SIG &ndash; Suite logicielles de gestion de donn&eacute;es cartographiques.</td>
</tr>
<tr>
<td class="new_nonopen">SG-1582</td><td class="new_nonopen">IGN (service web)</td><td class="new_nonopen">IGN</td><td>Version LTS ou ESR disponible</td><td class="statut_A">A</td><td></td><td class="comm_italic">Services web de visualisation de donn&eacute;es g&eacute;ographiques en acc&egrave;s libre. https://geoservices.ign.fr/services-web</td>
</tr>
<tr>
<td class="new_open">SG-1581</td><td class="new_open">OpenStreetMap (service web)</td><td class="new_open">OpenStreetmap</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Base de donn&eacute;es g&eacute;ogrpahique libre et outils de cartographie.  https://www.openstreetmap.fr/
</td>
</tr>
<tr>
<td class="inc_open">SG-1225</td><td class="inc_open">QGIS</td><td class="inc_open">qgis.org</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">SIG - Inscrit au SILL. Quantum GIS &ndash; Logiciel libre de SIG de type "Desktop"</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1212</td><td class="inc_nonopen">GeoConcept</td><td class="inc_nonopen">GeoConcept</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">SIG &ndash; Application permettant de lire et cr&eacute;er de la donn&eacute;e VECTEURS, RASTERS et ATTRIBUTAIRES, compatible avec les bases de donn&eacute;es spatiales (Oracle ou PostGIS) &agrave; l'exception de MapInfo.</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1210</td><td class="inc_nonopen">GCIS (GeoConcept Internet Server) </td><td class="inc_nonopen">GeoConcept</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Geoconcept Internet Server. Serveur cartographique. GeoConcept Internet Server</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1217</td><td class="inc_nonopen">MapInfo</td><td class="inc_nonopen">Pitney Bowes MapInfo</td><td>17</td><td class="statut_A">A</td><td></td><td class="comm_italic">SIG &ndash; Conception de cartes, g&eacute;ocodage, analyse.</td>
</tr>
<tr>
<td class="inc_open">SG-1219</td><td class="inc_open">MapServer</td><td class="inc_open">Universit&eacute; du Minnesota et NASA</td><td></td><td class="statut_M">M</td><td></td><td class="comm_italic">Serveur cartographique. Solution en perte de vitesse.</td>
</tr>
<tr>
<td class="inc_open">SG-1311</td><td class="inc_open">TileCache</td><td class="inc_open">tilecache.org</td><td></td><td class="statut_M">M</td><td></td><td class="comm_italic">Application Python de cache pour la fourniture de tuiles cartographiques. Serveur de cache en utilisation avec MapServer</td>
</tr>
<tr>
<td class="inc_open">SG-1296</td><td class="inc_open">GeoServer</td><td class="inc_open"></td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Serveur de donn&eacute;es cartographique (Java)</td>
</tr>
<tr>
<td class="inc_open">SG-1312</td><td class="inc_open">GeoWebCache</td><td class="inc_open">geowebcache.org</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Application Java de cache pour la fourniture de tuiles cartographiques. Serveur de cache en utilisation avec GeoServer</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1297</td><td class="inc_nonopen">DynMap / Geo</td><td class="inc_nonopen">Business-Geografic.com</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Serveur cartographique. Contexte d'emploi limit&eacute; &agrave; la pr&eacute;fecture de police de Paris. Solution reprise en 2012 par Business-Geografic.</td>
</tr>
<tr>
<td class="inc_open">SG-1211</td><td class="inc_open">G&eacute;oSource</td><td class="inc_open">BRGM</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">
Outil simple de catalogage de donn&eacute;es et services &agrave; r&eacute;f&eacute;rences spatiales - compatible ISO 19118 &amp; 19139 &ndash; Cf http://www.geosource.fr
</td>
</tr>
<tr>
<td class="inc_open">SG-1558</td><td class="inc_open">MapProxy</td><td class="inc_open">Omniscale</td><td></td><td class="statut_O">O</td><td>Non</td><td class="comm_italic">Proxy avec des fonctions de cache, d&rsquo;acc&eacute;l&eacute;ration et de transformation de donn&eacute;es g&eacute;ographiques. Produit &eacute;diteur avec version communautaire. Utilis&eacute; au ST(SI)&sup2;.</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1559</td><td class="inc_nonopen">FME Desktop</td><td class="inc_nonopen">Safe software (safe.com)</td><td></td><td class="statut_A">A</td><td>Non</td><td class="comm_italic">ETL d&eacute;di&eacute; au traitement des donn&eacute;es g&eacute;ographiques &ndash; Utilis&eacute; au ST(SI)&sup2; et &agrave; la PP.</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1560</td><td class="inc_nonopen">FME Server</td><td class="inc_nonopen">Safe software (safe.com)</td><td></td><td class="statut_A">A</td><td>Non</td><td class="comm_italic">FME Server permet d&rsquo;automatiser et de planifier des traitements r&eacute;alis&eacute;s avec FME Desktop.</td>
</tr>
<tr>
<td class="inc_open">SG-1557</td><td class="inc_open">ADDOK</td><td class="inc_open">Etalab.gouv.fr</td><td></td><td class="statut_R">R</td><td>Non</td><td class="comm_italic">G&eacute;ocodeur et moteur de recherche d&eacute;di&eacute; aux adresses. Mis en œuvre par &eacute;talab sur la BAN (Base adresse nationale) et par le ST(SI)&sup2; sur des donn&eacute;es d&rsquo;adresse enrichies. Le code est publi&eacute; sur Github.</td>
</tr>
</tbody>
</table>
<h3>
<a name="SGSA"> Chapitre 5 : Services d'acc&egrave;s - [ SA ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_nonopen">SG-1503</td><td class="inc_nonopen">DatAdvantage</td><td class="inc_nonopen">Varonis</td><td>6</td><td class="statut_A">A</td><td></td><td class="comm_italic">Audit et protection des donn&eacute;es. P&eacute;rim&egrave;tre r&eacute;duit &agrave; l&rsquo;administration centrale sous contr&ocirc;le DTNUM.</td>
</tr>
<tr>
<td class="inc_open">SG-1574</td><td class="inc_open">KEYCLOAK</td><td class="inc_open">www.keycloak.org</td><td>Version SILL</td><td class="statut_A">A</td><td>Non</td><td class="comm_italic">Keycloak est un logiciel &agrave; code source ouvert permettant d'instaurer une m&eacute;thode d'authentification unique au travers la gestion par identit&eacute; et par acc&egrave;s. C&rsquo;est une solution IAM compl&egrave;te. Le produit est inscrit au SILL mais a &eacute;t&eacute; plac&eacute; en Assujetti car au sein du Minist&egrave;re de l&rsquo;Int&eacute;rieur nous devons utiliser / pr&eacute;coniser en premier lieu LEMONLDAP-NG qui est une solution mise en œuvre au sein de notre administration.</td>
</tr>
<tr>
<td class="inc_open">SG-1402</td><td class="inc_open">LemonLDAP::NG</td><td class="inc_open">OW2</td><td>1.19</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Composant SSO (SAML, OpenID Connect ..) embarqu&eacute; dans les SSO minist&eacute;riels&nbsp;: PASSAGE 2, CHEOPS NG, PROXIMA, PASSAGE PP</td>
</tr>
<tr>
<td class="inc_open">SG-1201</td><td class="inc_open">MIT Kerberos</td><td class="inc_open">mit.edu</td><td></td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">
Kerberos est un 
protocole
 mis en œuvre dans plusieurs distributions&nbsp;: propri&eacute;taire (Microsoft), ou libres&nbsp;: MIT, Heimdal. Cf 

http://web.mit.edu/kerberos/

</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1354</td><td class="inc_nonopen">Validation Server (DVS)</td><td class="inc_nonopen">Dictao</td><td>4.11</td><td class="statut_A">A</td><td></td><td class="comm_italic">Composant proposant des services de validation de signatures, jetons, et certificats.</td>
</tr>
</tbody>
</table>
<h3>
<a name="SGGP"> Chapitre 6 : Gestion de parc &ndash; T&eacute;l&eacute;-d&eacute;ploiement/T&eacute;l&eacute;distribution - [ GP ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">SG-1233</td><td class="inc_open">GLPI</td><td class="inc_open">glpi-project.org</td><td>Version SILL</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. 
</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1333</td><td class="inc_nonopen">Kace</td><td class="inc_nonopen">Quest software</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">
Appliance de gestion de syst&egrave;me.
Contexte d'emploi  limit&eacute; &agrave; l'exp&eacute;rimentation par la Pr&eacute;fecture de Police</td>
</tr>
</tbody>
</table>
<h3>
<a name="SGRF"> Chapitre 7 : R&eacute;f&eacute;rentiels transverses - [ RF ]</a>
</h3>
<p class="comm_italic"></p>
<h3>
<a name="SGQD"> Chapitre 8 : Qualit&eacute; des donn&eacute;es - [ QD ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_nonopen">SG-1236</td><td class="inc_nonopen">DataMasker</td><td class="inc_nonopen">Cortina</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Outil d'anonymisation uniquement compatible avec le SGBD Oracle.</td>
</tr>
</tbody>
</table>
<h3>
<a name="SGGC"> Chapitre 9 : Gestion de contenu (ECM/GED) - [ GC ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">SG-1237</td><td class="inc_open">Alfresco</td><td class="inc_open">Communaut&eacute; Alfresco</td><td>4.x</td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic">Suite d'outils pour le collaboratif via portail Web.</td>
</tr>
<tr>
<td class="inc_open">SG-1489</td><td class="inc_open">Alfresco</td><td class="inc_open">Communaut&eacute; Alfresco</td><td>5.x</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Suite d'outils pour le collaboratif via portail Web.</td>
</tr>
<tr>
<td class="inc_open">SG-1395</td><td class="inc_open">eZ Publish</td><td class="inc_open">ez.no</td><td>5.1</td><td class="statut_A">A</td><td>Oui</td><td class="comm_italic">Version 5.1 r&eacute;serv&eacute;e &agrave; la migration des sites existants. En raison d'une incertitude sur le maintien de la version communautaire, le produit est plac&eacute; en observation (assujetti).</td>
</tr>
<tr>
<td class="new_open">SG-1598</td><td class="new_open">BlueGriffon</td><td class="new_open">Disruptive Innovations </td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Editeur de pages HTML</td>
</tr>
<tr>
<td class="maj_open">SG-1394</td><td class="maj_open">Joomla&nbsp;!</td><td class="maj_open">Joomla.org</td><td>4.x</td><td class="statut_R">R</td><td></td><td class="comm_italic">Cr&eacute;ation de sites Intranet institutionnels.</td>
</tr>
<tr>
<td class="inc_open">SG-1238</td><td class="inc_open">Dokuwiki</td><td class="inc_open">dokuwiki.org</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">
Wiki simple et ne n&eacute;cessitant pas de base de donn&eacute;e. Licence GNU GPL V2.
Utilisation des plugins inclus dans le package distribu&eacute; par le fournisseur</td>
</tr>
<tr>
<td class="inc_open">SG-1239</td><td class="inc_open">Mediawiki</td><td class="inc_open"></td><td>Version SILL</td><td class="statut_A">A</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. </td>
</tr>
<tr>
<td class="inc_open">SG-1403</td><td class="inc_open">Drupal</td><td class="inc_open">Drupal.org</td><td>8.x</td><td class="statut_R">R</td><td></td><td class="comm_italic">CMS autoris&eacute; sur le p&eacute;rim&egrave;tre ST(SI)&sup2; </td>
</tr>
</tbody>
</table>
<h3>
<a name="SGCM"> Chapitre 10 : Composants m&eacute;tiers - [ CM ]</a>
</h3>
<p class="comm_italic"></p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">SG-1501</td><td class="inc_open">Maarch</td><td class="inc_open">Maarch</td><td></td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Solution mise en oeuvre dans l'offre minist&eacute;rielle de GEC (Gestion &eacute;lectronique de courrier).</td>
</tr>
<tr>
<td class="inc_open">SG-1455</td><td class="inc_open">OSS</td><td class="inc_open">opensearchserver.com</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">P&eacute;rim&egrave;tre restreint au ST(SI)&sup2;. OSS(Open Search Server), &agrave; privil&eacute;gier en moteur de recherche vertical et pour les besoins d'ordonnancement de t&acirc;ches de crawl.</td>
</tr>
<tr>
<td class="inc_open">SG-1250</td><td class="inc_open">Jdonref</td><td class="inc_open">Pr&eacute;fecture de Police</td><td>V3</td><td class="statut_R">R</td><td></td><td class="comm_italic">Normalisation et g&eacute;olocalisation des adresses postales.</td>
</tr>
<tr>
<td class="inc_open">SG-1346</td><td class="inc_open">LimeSurvey CE</td><td class="inc_open">limesurvey.org</td><td>Derni&egrave;re version stable</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Composant de gestion de sondages et d'enqu&ecirc;tes en ligne</td>
</tr>
<tr>
<td class="inc_open">SG-1500</td><td class="inc_open">Moodle</td><td class="inc_open">moodle.org</td><td>3.x</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Apprentissage en ligne (e-learning)</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1245</td><td class="inc_nonopen">TDI</td><td class="inc_nonopen">Minist&egrave;re</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Traitement des identit&eacute;s (recherche sur la base de la phon&eacute;tisation des noms et pr&eacute;noms). Ce composant a &eacute;t&eacute; utilis&eacute;, sous diff&eacute;rentes versions, dans plusieurs applications&nbsp;notamment  FAED, SIV, FNAEG, FPR, Schengen&nbsp;&hellip;
</td>
</tr>
</tbody>
</table>
<h3>
<a name="SGAD"> Chapitre 11 : Analyse de donn&eacute;es - [ AD ]</a>
</h3>
<p class="comm_italic">Outils de collecte, de stockage, et d&rsquo;analyse de donn&eacute;es</p>
<table>
<thead>
<tr>
<th>R&eacute;f&eacute;rence</th><th>Composant</th><th>Fournisseur</th><th>Version</th><th>Statut</th><th>Supp. LL</th><th>Commentaires</th>
</tr>
</thead>
<tbody>
<tr>
<td class="inc_open">SG-1567</td><td class="inc_open">GRAFANA</td><td class="inc_open">Grafana Labs</td><td>Version SILL</td><td class="statut_R">R</td><td>Non</td><td class="comm_italic">Inscrit au SILL. Outil de visualisation de donn&eacute;es, de g&eacute;n&eacute;ration de tableaux de bord. Souvent utilis&eacute; pour r&eacute;aliser de la supervision des infrastructure et des composants (en compl&eacute;ment de PROMETHEUS). Peut &ecirc;tre une alternative a KIBANA /ELASTICSEARCH.</td>
</tr>
<tr>
<td class="inc_open">SG-1566</td><td class="inc_open">MATOMO</td><td class="inc_open">matomo.org</td><td>Version SILL</td><td class="statut_R">R</td><td>Non</td><td class="comm_italic">Inscrit au SILL. Outil d&rsquo;analyse d&rsquo;audience, de statistique de fr&eacute;quentation de site web.</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1167</td><td class="inc_nonopen">BO</td><td class="inc_nonopen">SAP</td><td>XI-R3.1</td><td class="statut_A">A</td><td></td><td class="comm_italic">D&eacute;cisionnel. Le minist&egrave;re est signataire de l'Accord Cadre Interminist&eacute;riel (ACIM) relatif &agrave; l'acquisition de produits SAP-BO. Voir l'ACIM et contacter imp&eacute;rativement cct@interieur.gouv.fr pour conna&icirc;tre la liste des produits retenus.</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1425</td><td class="inc_nonopen">BO</td><td class="inc_nonopen">SAP</td><td>XI R4.1</td><td class="statut_A">A</td><td></td><td class="comm_italic">D&eacute;cisionnel.</td>
</tr>
<tr>
<td class="inc_open">SG-1417</td><td class="inc_open">PENTAHO CE</td><td class="inc_open">Pentaho, Hitachi Data Systems company</td><td></td><td class="statut_A">A</td><td>Oui</td><td class="comm_italic">Portail d&eacute;cisionnel. Produit retir&eacute; du SILL en raison de doutes sur la p&eacute;rennit&eacute; de son offre communautaire.</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1518</td><td class="inc_nonopen">Splunk</td><td class="inc_nonopen">Splunk</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Plateforme d&rsquo;intelligence op&eacute;rationnelle en temps r&eacute;el (collecte et analyse de donn&eacute;es machine)</td>
</tr>
<tr>
<td class="inc_open">SG-1512</td><td class="inc_open">Talend Big Data Integration</td><td class="inc_open">Talend</td><td>6</td><td class="statut_A">A</td><td></td><td class="comm_italic">Version soumise &agrave; souscription. Version communautaire&nbsp;: Talend Open Studio for Big Data</td>
</tr>
<tr>
<td class="inc_open">SG-1513</td><td class="inc_open">Talend Data Preparation</td><td class="inc_open">Talend</td><td>6</td><td class="statut_A">A</td><td></td><td class="comm_italic">Version commerciale (souscription) du composant pr&eacute;sent dans Talend Data Preparation Free Desktop</td>
</tr>
<tr>
<td class="inc_open">SG-1515</td><td class="inc_open">Talend Data Quality</td><td class="inc_open">Talend</td><td>6</td><td class="statut_A">A</td><td></td><td class="comm_italic">Version soumise &agrave; souscription. Version communautaire&nbsp;: Talend Open Studio for Data Quality</td>
</tr>
<tr>
<td class="inc_open">SG-1517</td><td class="inc_open">Talend Master Data Management (MDM)</td><td class="inc_open">Talend</td><td>6</td><td class="statut_A">A</td><td></td><td class="comm_italic">Version soumise &agrave; souscription. Version communautaire&nbsp;: Talend Open Studio for MDM</td>
</tr>
<tr>
<td class="inc_open">SG-1377</td><td class="inc_open">Lucene</td><td class="inc_open">apache.org</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Moteur d'indexation &agrave; la base de diverses impl&eacute;mentations de moteurs de recherches (Solr, Elastic Search, OpenSearchServer...)</td>
</tr>
<tr>
<td class="inc_open">SG-1454</td><td class="inc_open">SolR</td><td class="inc_open">Apache.org</td><td>Version SILL</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. SolR est &eacute;crit en java et repose sur Lucene. Il doit &ecirc;tre mis en oeuvre comme une brique de service autonome (interface HTTP, format XML ou JSON)</td>
</tr>
<tr>
<td class="inc_open">SG-1456</td><td class="inc_open">ElasticSearch</td><td class="inc_open">elastic.co</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. </td>
</tr>
<tr>
<td class="inc_open">SG-1530</td><td class="inc_open">Logstash</td><td class="inc_open">elastic.co</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Collecte, traitement, transformation de donn&eacute;es provenant d'une multitude de sources. Souvent associ&eacute; &agrave; Elasticsearch/Logstash/Kibana (ELK).</td>
</tr>
<tr>
<td class="inc_open">SG-1531</td><td class="inc_open">Kibana</td><td class="inc_open">elastic.co</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Visualisation de donn&eacute;es. Souvent associ&eacute; &agrave; Elasticsearch/Logstash/Kibana (ELK).</td>
</tr>
<tr>
<td class="inc_open">SG-1483</td><td class="inc_open">Hibernate Search</td><td class="inc_open">Hibernate</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Moteur d&rsquo;indexation et de recherche int&eacute;gr&eacute; &agrave; un applicatif d&eacute;velopp&eacute; en java.Hibernate search repose sur lucene. A chaque fois que cela est possible, afin de respecter les principes de modularit&eacute;, il faudra pr&eacute;f&eacute;rer la mise en place de services de recherche autonomes (Voir SolR, OpenSearchServer ou ElasticSearch). P&eacute;rim&egrave;tre restreint au ST(SI)&sup2;
</td>
</tr>
<tr>
<td class="inc_open">SG-1163</td><td class="inc_open">Eclipse BIRT</td><td class="inc_open">eclipse.org</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Solution ouverte de data visualisation</td>
</tr>
<tr>
<td class="inc_open">SG-1164</td><td class="inc_open">JasperSoft / JasperReports
</td><td class="inc_open">TIBCO</td><td></td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Reporting. Version communautaire.</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1162</td><td class="inc_nonopen">
SAP BW (Business Warehouse)
</td><td class="inc_nonopen">SAP</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Outil d&eacute;cisionnel de SAP &agrave; des fins d&rsquo; analyse et de reporting.</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1300</td><td class="inc_nonopen">PowerCenter</td><td class="inc_nonopen">Informatica</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Int&eacute;gration de donn&eacute;es - contexte d'emploi Projet AGDREF2</td>
</tr>
<tr>
<td class="inc_open">SG-1509</td><td class="inc_open">HADOOP</td><td class="inc_open">Cloudera</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Distribution Cloudera de la pile d&rsquo;outils bigdata HADOOP</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1546</td><td class="inc_nonopen">DSS (Data Science Studio)</td><td class="inc_nonopen">Dataiku (Dataiku.com)</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Plateforme collaborative de data science avec des fonctions de pr&eacute;paration et qualit&eacute; de donn&eacute;es et d&rsquo;analyse pr&eacute;dictive.</td>
</tr>
<tr>
<td class="inc_nonopen">SG-1547</td><td class="inc_nonopen">Tableau</td><td class="inc_nonopen">Tableau software (tableau.com).</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Outil de visualisation et d&rsquo;analyse de donn&eacute;es &agrave; destination des statisticiens et des m&eacute;tiers.</td>
</tr>
</tbody>
</table>






{% include "components/back_to_top.njk" %}
