</table>
<hr>
<h2>
<a name="RT"> Partie 3 : R&eacute;seau de transport - [ RT ]</a>
</h2>
<p class="comm_italic">Note importante :Conform&eacute;ment &agrave; la circulaire interminist&eacute;rielle NOR : INDI1127026C du 08/12/2011, les cahiers des charges des march&eacute;s publics r&eacute;dig&eacute;s dans le cadre de projets informatiques relevant du protocole IP au profit du minist&egrave;re de l'int&eacute;rieur  doivent int&eacute;grer l'obligation de compatibilit&eacute; avec le protocole IpV6.</p>
<hr>
<h3>
<a name="RTSV"> Chapitre 1 : Services - [ SV ]</a>
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
<td class="inc_open">RT-1085</td><td class="inc_open">Squid</td><td class="inc_open"></td><td>Version distrib</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. </td>
</tr>
</tbody>
</table>
<h3>
<a name="RTPF"> Chapitre 2 : Performances - [ PF ]</a>
</h3>
<p class="comm_italic"></p>
<h3>
<a name="RTTO"> Chapitre 3 : Topologie - [ TO ]</a>
</h3>
<p class="comm_italic"></p>
<h3>
<a name="RTSI"> Chapitre 4 : S&eacute;curit&eacute; - [ SI ]</a>
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
<td class="new_nonopen">RT-1580</td><td class="new_nonopen">VPN TheGreenBow</td><td class="new_nonopen">TheGreenBow</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">VPN. Sous licence.</td>
</tr>
<tr>
<td class="inc_open">RT-1086</td><td class="inc_open">FreeRADIUS</td><td class="inc_open">Freeradius</td><td>Version distrib</td><td class="statut_R">R</td><td></td><td class="comm_italic">Version distribution Debian</td>
</tr>
<tr>
<td class="inc_open">RT-1090</td><td class="inc_open">OPENVPN</td><td class="inc_open"></td><td>Version distrib</td><td class="statut_A">A</td><td></td><td class="comm_italic">Version distribution Debian</td>
</tr>
<tr>
<td class="inc_open">RT-1091</td><td class="inc_open">strongSwan</td><td class="inc_open">strongswan.org</td><td>Version distrib</td><td class="statut_A">A</td><td></td><td class="comm_italic">VPN IPsec - Version distribution Debian</td>
</tr>
<tr>
<td class="inc_open">RT-1087</td><td class="inc_open">RANCID</td><td class="inc_open">shrubbery.net</td><td>3</td><td class="statut_A">A</td><td></td><td class="comm_italic">Gestion des configurations des routeurs. (Really Awesome New Cisco confIg Differ). Rancid est bas&eacute; sur cvs (gestion de version).
</td>
</tr>
</tbody>
</table>
<h3>
<a name="RTRL"> Chapitre 5 : R&eacute;seau local - [ RL ]</a>
</h3>
<p class="comm_italic"></p>
<h3>
<a name="RTVR"> Chapitre 6 : Virtualisation - [ VR ]</a>
</h3>
<p class="comm_italic"></p>
<hr>
<h2>
<a name="SI"> Partie 4 : S&eacute;curit&eacute; &amp; interop&eacute;rabilit&eacute; - [ SI ]</a>
</h2>
<p class="comm_italic">Pour les logiciels pris en charge au march&eacute; de support logiciels libres, il est indiqu&eacute; "Oui" dans la colonne "Supp. LL"</p>
<hr>
<h3>
<a name="SIAP"> Chapitre 1 : Appliance - [ AP ]</a>
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
<td class="inc_open">SI-1291</td><td class="inc_open">Apache mod_security</td><td class="inc_open">Apache Software Foundation</td><td></td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Filtrage des flux HTTP et HTTPS et correction des URL mal form&eacute;s.</td>
</tr>
<tr>
<td class="inc_open">SI-1301</td><td class="inc_open">DansGuardian</td><td class="inc_open">dansguardian.org</td><td>2.x</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Filtrage de contenu</td>
</tr>
</tbody>
</table>
<h3>
<a name="SIAV"> Chapitre 2 : Antivirus - [ AV ]</a>
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
<td class="inc_open">SI-1028</td><td class="inc_open">ClamAV</td><td class="inc_open">clamav.net</td><td>Version distrib</td><td class="statut_R">R</td><td>Oui</td><td class="comm_italic">Inscrit au SILL. Pour OS Linux / Unix. </td>
</tr>
<tr>
<td class="inc_nonopen">SI-1398</td><td class="inc_nonopen">ePolicy Orchestrator Agent</td><td class="inc_nonopen">McAfee</td><td>5.1</td><td class="statut_R">R</td><td></td><td class="comm_italic">Logiciel de distribution et de mise &agrave; jour de l'antivirus (infrastructure nationale)</td>
</tr>
<tr>
<td class="inc_nonopen">SI-1399</td><td class="inc_nonopen">Server Security - Linux</td><td class="inc_nonopen">SOPHOS</td><td>9.6</td><td class="statut_R">R</td><td></td><td class="comm_italic">Anti-virus serveur linux</td>
</tr>
<tr>
<td class="inc_nonopen">SI-1400</td><td class="inc_nonopen">Server Security - Windows</td><td class="inc_nonopen">SOPHOS</td><td>10.3</td><td class="statut_R">R</td><td></td><td class="comm_italic">Antivirus serveur Windows. SOPHOS est remplacé par ESET à partir de Juillet 2023 à la DTNUM.</td>
</tr>
<tr>
<td class="inc_nonopen">SI-1430</td><td class="inc_nonopen">VirusScan &ndash; Linux</td><td class="inc_nonopen">McAfee</td><td>2.0.2</td><td class="statut_R">R</td><td></td><td class="comm_italic">Pour poste de travail Linux - 64 bits uniquement</td>
</tr>
</tbody>
</table>
<h3>
<a name="SICH"> Chapitre 3 : Chiffrement - [ CH ]</a>
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
<td class="maj_open">SI-1428</td><td class="inc_open">Keepass</td><td class="maj_open">Dominique Reichl</td><td>Version SILL</td><td class="statut_R">R</td><td></td><td class="comm_italic">Solution de gestion de mots de passe.</td>
</tr>
<tr>
<td class="inc_open">SI-1251</td><td class="inc_open">TrueCrypt</td><td class="inc_open">truecrypt.org</td><td></td><td class="statut_M">M</td><td></td><td class="comm_italic">Incompatible avec Windows 10. Client de chiffrement dans la version 7.1a certifi&eacute;e par l'ANSSI. </td>
</tr>
<tr>
<td class="inc_nonopen">SI-1493</td><td class="inc_nonopen">Prim&rsquo;X Cryhod</td><td class="inc_nonopen">Prim&rsquo;X Technologies (primx.eu)</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Outil de chiffrement physique (disque dur..).Remplacement de TrueCrypt.</td>
</tr>
<tr>
<td class="inc_nonopen">SI-1494</td><td class="inc_nonopen">Prim&rsquo;X Zone Central</td><td class="inc_nonopen">Prim&rsquo;X Technologies (primx.eu)</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Outil de chiffrement de zone. Associ&eacute; &agrave; l&rsquo;AD.</td>
</tr>
<tr>
<td class="inc_nonopen">SI-1495</td><td class="inc_nonopen">Prim&rsquo;X Zed</td><td class="inc_nonopen">Prim&rsquo;X Technologies (primx.eu)</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Conteneurs chiffr&eacute;s pour l'&eacute;change ou la sauvegarde.</td>
</tr>
</tbody>
</table>
<h3>
<a name="SISG"> Chapitre 4 : Signature - [ SG ]</a>
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
<td class="inc_nonopen">SI-1352</td><td class="inc_nonopen">Signature Server (D2S)</td><td class="inc_nonopen">Dictao</td><td>4.11</td><td class="statut_A">A</td><td></td><td class="comm_italic">Composant proposant des services de signatures, horodatage, v&eacute;rification d'habilitation &agrave; signer, conservation des signatures.</td>
</tr>
<tr>
<td class="new_open">SI-1602</td><td class="new_open">AdSigner Standalone </td><td class="new_open">AdSigner</td><td>4.5.8.0</td><td class="statut_R">R</td><td></td><td class="comm_italic">client lourd de signature personnelle de document Pdf avec visuel fixe ou sans visuel. Attention&nbsp;: la version java web start Signature en mode "Java web start" est interdite pour tout usage.</td>
</tr>
<tr>
<td class="maj_open">SI-1445</td><td class="maj_open">
DSS  e-Signature
</td><td class="maj_open">Communaut&eacute; europ&eacute;enne</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">
DSS (Digital Signature Service) framework de cr&eacute;ation et de validation de signature &eacute;lectronique. Port&eacute; par la communaut&eacute; europ&eacute;enne.  Developpement d&rsquo;une API r&eacute;alis&eacute;e au sein de la DTNUM, permettant  l&rsquo;appel aux services horodatage-mi et SIGNHOR-DVS)
</td>
</tr>
</tbody>
</table>
<h3>
<a name="SIIG"> Chapitre 5 : IGC - [ IG ]</a>
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
<td class="inc_nonopen">SI-1292</td><td class="inc_nonopen">Trustykey</td><td class="inc_nonopen">CS</td><td>6.0.14</td><td class="statut_R">R</td><td></td><td class="comm_italic">TrustyKey CA version 6.0.14 certifi&eacute; CC par l&rsquo;ANSSI</td>
</tr>
<tr>
<td class="inc_nonopen">SI-1293</td><td class="inc_nonopen">TrustyServer</td><td class="inc_nonopen">CS</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Serveur de validation des certificats
</td>
</tr>
<tr>
<td class="inc_open">SI-1253</td><td class="inc_open">EJBCA</td><td class="inc_open">ejbca.org</td><td></td><td class="statut_A">A</td><td>Oui</td><td class="comm_italic">Enterprise JavaBeans Certificate Authority &ndash; application de PKI &ndash; ou IGC </td>
</tr>
</tbody>
</table>
<h3>
<a name="SIHO"> Chapitre 6 : Horodatage - [ HO ]</a>
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
<td class="inc_nonopen">SI-1353</td><td class="inc_nonopen">TimeStamp Server (DTSS)</td><td class="inc_nonopen">Dictao</td><td>4.11</td><td class="statut_A">A</td><td></td><td class="comm_italic">Composant proposant des services d'horodatage (g&eacute;n&eacute;ration de jetons, compl&eacute;tion de signature avec horodatage, v&eacute;rification d'habilitation &agrave; signer, conservation des jetons d'horodatage).</td>
</tr>
<tr>
<td class="inc_nonopen">SI-1451</td><td class="inc_nonopen">Trusty Time</td><td class="inc_nonopen">CS</td><td>3.1.3</td><td class="statut_R">R</td><td></td><td class="comm_italic">Composant d'horodatage utilis&eacute; dans l'offre SAAS minist&eacute;rielle.</td>
</tr>
</tbody>
</table>
<h3>
<a name="SIAL"> Chapitre 7 : Archivage l&eacute;gal - [ AL ]</a>
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
<td class="inc_open">SI-1490</td><td class="inc_open">Maarch RM</td><td class="inc_open">Maarch</td><td></td><td class="statut_R">R</td><td></td><td class="comm_italic">Solution d&rsquo;archivage. Peut &ecirc;tre associ&eacute;e &agrave; VITAM.</td>
</tr>
</tbody>
</table>