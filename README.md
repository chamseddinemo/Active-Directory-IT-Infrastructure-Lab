# Active-Directory-IT-Infrastructure-Lab
Active Directory &amp; IT Infrastructure Lab

<h1>🏢 TECHCORP ENTERPRISE </h1>

<h2>🖥️ Junior Systems Administrator – Active Directory & IT Infrastructure Lab</h2>

<p>
TechCorp Enterprise Environment (Home Lab Simulation)<br/>
Windows Server | Active Directory | Group Policy | Windows 10/11
</p>

<hr/>

<h2>🎯 Contexte du projet</h2>
<p>
Conception et administration d’un environnement d’entreprise simulé afin de reproduire une infrastructure IT réelle basée sur Active Directory.
<br/><br/>
Le lab simule une PME avec plusieurs départements (IT, HR, Finance) et applique des standards de sécurité et de gestion des accès utilisés en entreprise.
</p>

<hr/>

<h2>⚙️ Responsabilités / Réalisations</h2>

<h3>🏗️ Infrastructure Active Directory</h3>
<ul>
<li>Installation et configuration d’un Domain Controller (DC01)</li>
<li>Création du domaine interne : <b>techcorp.local</b></li>
<li>Configuration et intégration du service DNS avec Active Directory</li>
<li>Administration du domaine via Active Directory Users and Computers (ADUC)</li>
</ul>

<h3>🏢 Architecture organisationnelle (OU Design)</h3>
<ul>
<li>Conception d’une structure hiérarchique entreprise :
  <ul>
    <li>OU_IT</li>
    <li>OU_HR</li>
    <li>OU_Finance</li>
  </ul>
</li>
<li>Organisation des objets AD selon les départements</li>
<li>Préparation de l’environnement pour la gestion des politiques de sécurité</li>
</ul>

<h3>👤 Gestion des identités (Identity Management)</h3>
<ul>
<li>Création et gestion des comptes utilisateurs Active Directory</li>
<li>Attribution des utilisateurs aux unités organisationnelles appropriées</li>
<li>Activation, configuration et maintenance des comptes utilisateurs</li>
</ul>

<h3>👥 Groupes de sécurité et contrôle d’accès</h3>
<ul>
<li>Création de groupes de sécurité :
  <ul>
    <li>GRP_IT</li>
    <li>GRP_HR</li>
    <li>GRP_FINANCE</li>
  </ul>
</li>
<li>Implémentation du contrôle d’accès basé sur les rôles (RBAC)</li>
<li>Gestion des permissions via l’appartenance aux groupes</li>
</ul>

<h3>🔐 Group Policy Objects (GPO) – Sécurité entreprise</h3>

<h4>🏢 GPO Domaine (Security Baseline)</h4>
<ul>
<li>Password Policy (complexité, expiration)</li>
<li>Account Lockout Policy</li>
<li>Audit des connexions et événements système</li>
</ul>

<h4>🖥️ GPO Département IT</h4>
<ul>
<li>Restrictions système (CMD / PowerShell / Control Panel)</li>
<li>Renforcement des permissions administratives</li>
<li>Monitoring des activités utilisateurs IT</li>
</ul>

<h4>👩 GPO Département HR</h4>
<ul>
<li>Redirection Desktop/Documents</li>
<li>Mapping de lecteurs réseau</li>
<li>Restrictions d’installation logicielle</li>
</ul>

<h4>💰 GPO Département Finance</h4>
<ul>
<li>Accès restreint aux ressources sensibles</li>
<li>Blocage des périphériques USB</li>
<li>Gestion sécurisée des partages réseau financiers</li>
</ul>

<h3>🔗 Architecture de sécurité</h3>
<ul>
<li>Domain-level policies</li>
<li>OU-level policies</li>
<li>Security Group filtering (RBAC)</li>
<li>Séparation complète des environnements utilisateurs</li>
</ul>

<h3>🧪 Tests et validation</h3>
<ul>
<li>Vérification des GPO via gpresult /r</li>
<li>Tests d’accès selon groupes utilisateurs</li>
<li>Validation des restrictions (CMD, USB, drives)</li>
<li>Test de segmentation réseau par département</li>
</ul>

<h2>🧠 Compétences démontrées</h2>
<ul>
<li>Active Directory Administration (Enterprise Level)</li>
<li>Windows Server Management</li>
<li>Group Policy Management (GPO)</li>
<li>Identity & Access Management (IAM)</li>
<li>Role-Based Access Control (RBAC)</li>
<li>IT Infrastructure Design</li>
<li>Security Hardening</li>
<li>Windows Troubleshooting</li>
</ul>
