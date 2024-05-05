---
title: referentiel des produits de l'ENT de l'administrateur, l'exploitation et l'hebergement
layout: layouts/page_date_readtime.njk
showBreadcrumb: true
date: git Last Modified
---

<hr>
<h2>
<a name="EX"> Partie 1 : Exploitation &amp; H&eacute;bergement - [ EX ]</a>
</h2>
<p class="comm_italic">Pour les logiciels pris en charge au march&eacute; de support logiciels libres, il est indiqu&eacute; "Oui" dans la colonne "Supp. LL"</p>
<hr>
<h3>
<a name="EXHD"> Chapitre 1 : Haute disponibilit&eacute; / R&eacute;partition de charge (PCA) - [ HD ]</a>
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
<td class="inc_open">EX-1110</td><td class="inc_open">Keepalived</td><td class="inc_open">keepalived.org</td><td>1.x</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Basculement et partage de charge</td>
</tr>
<tr>
<td class="inc_open">EX-1416</td><td class="inc_open">HAProxy</td><td class="inc_open">haproxy.com</td><td>Version SILL</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Basculement et partage de charge</td>
</tr>
<tr>
<td class="inc_open">EX-1487</td><td class="inc_open">Corosync Cluster Engine</td><td class="inc_open">Corosync.org</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Brique de mise en œuvre d&rsquo;un cluster de N nœuds</td>
</tr>
<tr>
<td class="inc_open">EX-1488</td><td class="inc_open">Pacemaker</td><td class="inc_open">clusterlabs.org</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Outil de gestion de ressource sur un cluster N nœuds &ndash; Associ&eacute; &agrave; Corosync</td>
</tr>
</tbody>
</table>
<h3>
<a name="EXPS"> Chapitre 2 : Plan de secours (PRA) - [ PS ]</a>
</h3>
<p class="comm_italic"></p>
<h3>
<a name="EXSV"> Chapitre 3 : Sauvegardes - [ SV ]</a>
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
<td class="inc_open">EX-1069</td><td class="inc_open">BACULA</td><td class="inc_open">bacula.org</td><td>Version distrib</td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic">Outil de sauvegarde. La version est celle nativement incluse dans la distribution Linux. BACULA tend a &ecirc;tre remplacer par son fork BAREOS qui, lui, est inscrit dans le SILL.</td>
</tr>
<tr>
<td class="inc_open">EX-1569</td><td class="inc_open">BAREOS</td><td class="inc_open">bareos.org</td><td>Version SILL</td><td class="statut_R">R</td><td>Non</td><td class="comm_italic">Inscrit au SILL. Outil de sauvegarde et de restauration de fichier en mode client-serveur dans un r&eacute;seau. Fork de BACULA.</td>
</tr>
<tr>
<td class="maj_nonopen">EX-1420</td><td class="maj_nonopen">NetBackup</td><td class="maj_nonopen">VERITAS</td><td>10.0</td><td class="statut_R">R</td><td></td><td class="comm_italic">Contexte d'emploi : h&eacute;bergement DTNUM</td>
</tr>
<tr>
<td class="inc_nonopen">EX-1114</td><td class="inc_nonopen">Time navigator</td><td class="inc_nonopen">Atempo</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Contexte d'emploi h&eacute;bergement ST(SI)&sup2;/STIG</td>
</tr>
</tbody>
</table>
<h3>
<a name="EXIN"> Chapitre 4 : Industrialisation - [ IN ]</a>
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
<td class="inc_nonopen">EX-1391</td><td class="inc_nonopen">HPOO</td><td class="inc_nonopen">HP</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">OO = Operation Orchestrator. Portail d'orchestration pour la creation automatis&eacute;e de VM.</td>
</tr>
<tr>
<td class="maj_nonopen">EX-1117</td><td class="maj_nonopen">Visual TOM (VTOM)</td><td class="maj_nonopen">Absyss</td><td>6.3.3m</td><td class="statut_R">R</td><td></td><td class="comm_italic">Ordonnanceur (Scheduler)- Contexte d'emploi h&eacute;bergement DTNUM</td>
</tr>
</tbody>
</table>
<h3>
<a name="EXSU"> Chapitre 5 : Supervision - [ SU ]</a>
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
<td class="inc_nonopen">EX-1360</td><td class="inc_nonopen">Proactivenet</td><td class="inc_nonopen">BMC Software</td><td>8.6.4</td><td class="statut_A">A</td><td></td><td class="comm_italic">Hypervision des datacenters.</td>
</tr>
<tr>
<td class="inc_open">EX-1568</td><td class="inc_open">PROMETHEUS</td><td class="inc_open">Prometheus.io</td><td>Version SILL</td><td class="statut_R">R</td><td>Non</td><td class="comm_italic">Inscrit au SILL. Outil de supervision des infrastructures et des composants, de surveillance informatique et de g&eacute;n&eacute;ration d&rsquo;alertes. Solution Cloud native. En alternative a KIBANA / ELASTICSEARCH.</td>
</tr>
<tr>
<td class="inc_open">EX-1572</td><td class="inc_open">ZABBIX</td><td class="inc_open">www.zabbix.com</td><td></td><td class="statut_R">R</td><td>Non</td><td class="comm_italic">Outil de supervision mis en œuvre dans les environnements Cloud du Minist&egrave;re de l&rsquo;Int&eacute;rieur pour superviser les infrastructures r&eacute;seau, en compl&eacute;ment de Centreon/Prometheus.</td>
</tr>
<tr>
<td class="inc_open">EX-1123</td><td class="inc_open">Nagios</td><td class="inc_open">nagios.org</td><td>3.5</td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic">Supervision infrastructure &ndash; Remplac&eacute; par Centreon Engine</td>
</tr>
<tr>
<td class="inc_open">EX-1285</td><td class="inc_open">Centreon</td><td class="inc_open">Centreon</td><td>2.3.x</td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Solution de supervision bas&eacute;e sur Nagios. La nouvelle version de Centreon (Engine) remplace le moteur nagios.</td>
</tr>
<tr>
<td class="inc_open">EX-1287</td><td class="inc_open">Fully Automated Nagios</td><td class="inc_open">sourceforge</td><td>2.1</td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic">Solution packag&eacute;e sur une base Nagios pour la supervision des LAN en datacenters zonaux.<br/>Produits contenus:<br/>- Nagios 3.2.3<br/>- Centreon 2.1.13<br/>- NagVis 1.58<br/>- Nagios Plugins 1.4.15</td>
</tr>
<tr>
<td class="inc_open">EX-1489</td><td class="inc_open">Centreon (Engine, Broker,Web)</td><td class="inc_open">centreon.com</td><td>&gt; = 2.8</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Plateforme de supervision (remplacement de Nagios)</td>
</tr>
<tr>
<td class="inc_nonopen">EX-1124</td><td class="inc_nonopen">ITSM (Information Technology Service Management)</td><td class="inc_nonopen">BMC Software</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Gestion de service ITIL</td>
</tr>
<tr>
<td class="inc_open">EX-1406</td><td class="inc_open">itop</td><td class="inc_open">Combodo</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Gestion de service ITIL - P&eacute;rim&egrave;tre restreint au ST(SI)2</td>
</tr>
<tr>
<td class="inc_open">EX-1120</td><td class="inc_open">Cacti</td><td class="inc_open">Cacti.net</td><td></td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Logiciel libre de mesure de performances r&eacute;seau et serveur</td>
</tr>
<tr>
<td class="inc_open">EX-1415</td><td class="inc_open">puppet</td><td class="inc_open">PuppetLabs</td><td>3.5</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Outil de gestion de configuration</td>
</tr>
<tr>
<td class="inc_open">EX-1533</td><td class="inc_open">Ansible</td><td class="inc_open">Ansible.com</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Outil de gestion de configuration</td>
</tr>
<tr>
<td class="inc_open">EX-1290</td><td class="inc_open">TELEMETROBOX</td><td class="inc_open">MIOMCTI</td><td></td><td class="statut_M">M</td><td>Oui</td><td class="comm_italic">Solution de supervision des r&eacute;seaux dans les services zonaux (d&eacute;veloppement SZSIC Rennes)</td>
</tr>
<tr>
<td class="inc_open">EX-1492</td><td class="inc_open">Telemetrobox-ng</td><td class="inc_open">MI &ndash; SGAMI Ouest</td><td>7</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Sonde de supervision</td>
</tr>
<tr>
<td class="inc_nonopen">EX-1490</td><td class="inc_nonopen">IMC &ndash; PLAT </td><td class="inc_nonopen">HPE</td><td>7.1</td><td class="statut_R">R</td><td></td><td class="comm_italic">Plateforme IMC de HPE (Intelligent Management Center) </td>
</tr>
<tr>
<td class="inc_nonopen">EX-1491</td><td class="inc_nonopen">SteelCentral AppResponse (Sonde riverbed)</td><td class="inc_nonopen">Riverbed</td><td>9.5.x</td><td class="statut_R">R</td><td></td><td class="comm_italic">Sonde APM (gestion de performance applicative)</td>
</tr>
</tbody>
</table>
<h3>
<a name="EXJT"> Chapitre 6 : Journalisation technique - [ JT ]</a>
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
<td class="inc_open">EX-1125</td><td class="inc_open">
Apache Log4j</td><td class="inc_open">Apache Software Foundation</td><td>2</td><td class="statut_R">R</td><td></td><td class="comm_italic">Framework de logging pour java</td>
</tr>
</tbody>
</table>
<h3>
<a name="EXVR"> Chapitre 7 : Virtualisation - [ VR ]</a>
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
<td class="inc_nonopen">EX-1551</td><td class="inc_nonopen">Hyper-V</td><td class="inc_nonopen">Microsoft</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Restriction aux serveurs d'applications bureautiques et locales</td>
</tr>
<tr>
<td class="maj_open">EX-1561</td><td class="maj_open">Kubernetes</td><td class="maj_open">CNCF (Cloud Native Computing Foundation)</td><td></td><td class="statut_R">R</td><td>Non</td><td class="comm_italic">Kubernetes est la principale plateforme d&rsquo;orchestration de conteneurs du march&eacute;. Elle est int&eacute;gr&eacute;e dans l&rsquo;offre Cloud Pi Native propos&eacute;e au MIOM.
<br>Inscrit au SILL.</br></td>
</tr>
<tr>
<td class="inc_open">EX-1132</td><td class="inc_open">KVM</td><td class="inc_open"></td><td>Version SILL</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Utilisation de la version native de la distribution Linux</td>
</tr>
<tr>
<td class="inc_nonopen">EX-1506</td><td class="inc_nonopen">Vmware Vsphere</td><td class="inc_nonopen">Vmware</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Environnement d&rsquo;ex&eacute;cution de machine virtuelle &ndash; Pour une primoinstallation, utiliser la derni&egrave;re version stable de l&rsquo;&eacute;diteur.</td>
</tr>
<tr>
<td class="inc_nonopen">EX-1421</td><td class="inc_nonopen">Vmware vCenter Server</td><td class="inc_nonopen">VMware</td><td></td><td class="statut_A">A</td><td></td><td class="comm_italic">Gestion centralis&eacute;e de la supervision</td>
</tr>
<tr>
<td class="inc_open">EX-1529</td><td class="inc_open">Openstack</td><td class="inc_open">openstack.org</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Inscrit au SILL. Plateforme ouverte de cloud computing.</td>
</tr>
<tr>
<td class="maj_open">EX-1540</td><td class="maj_open">Docker</td><td class="maj_open">docker.com</td><td></td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Plateforme de conteneurisation.</td>
</tr>
</tbody>
</table>
<h3>
<a name="EXST"> Chapitre 8 : Stockage - [ ST ]</a>
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
<td class="inc_open">EX-1571</td><td class="inc_open">CEPH</td><td class="inc_open">ceph.io</td><td>Version SILL</td><td class="statut_R">R</td><td>Non</td><td class="comm_italic">Solution de stockage distribu&eacute; impl&eacute;ment&eacute; dans les environnements Cloud du Minist&egrave;re de l&rsquo;Int&eacute;rieur. Il propose trois protocoles : Bloc, Fichiers &amp; Objet (S3).</td>
</tr>
<tr>
<td class="inc_open">EX-1570</td><td class="inc_open">STARWIND VIRTUAL SAN</td><td class="inc_open">www.starwindsoftware.com</td><td></td><td class="statut_R">R</td><td>Non</td><td class="comm_italic">Outil de stockage de machines virtuelles. Il cr&eacute;e un pool de stockage a faible co&ucirc;t. Il pallie le besoin de SAN ou de NAS. Il est compl&egrave;tement int&eacute;gr&eacute; &agrave; l&rsquo;hyperviseur.
</td>
</tr>
</tbody>
</table>
<hr>


{% include "components/back_to_top.njk" %}
