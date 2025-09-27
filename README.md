🦖 MSPR3 – Projet Jurassico / PteroPark
📌 Contexte

Ce projet s’inscrit dans le cadre de la MSPR TPRE833 – Déploiement d’une architecture fonctionnelle et technique en cybersécurité dans le cursus Expert(e) en cybersécurité (RNCP Niveau 7) à l’EPSI Paris.

Le client fictif Jurassico, propriétaire du parc d’attractions PteroPark, nous a sollicités pour renforcer la sécurité de son infrastructure IT/OT.
Avec plus de 10 000 employés, 10 millions de visiteurs par an et une infrastructure hybride (SCADA, IoT, SI bureautique, web, DMZ, réseaux industriels), la sécurisation de l’ensemble est critique.

🎯 Objectifs du projet

Déployer des solutions techniques et organisationnelles adaptées au contexte du parc.

Réaliser des PoC (Proof of Concept) pour démontrer la faisabilité des solutions.

Fournir des procédures d’intégration claires pour les équipes internes.

Élaborer des fiches réflexes pour renforcer la capacité de réaction face aux incidents.

🛠️ Solutions mises en place (PoC)

WAF (Web Application Firewall) – protection du serveur web Apache vulnérable (CVE-2021-41773).

Solution retenue : ModSecurity + OWASP CRS.

Objectif : bloquer les attaques applicatives sans perturber la billetterie.

IDS (Intrusion Detection System) – surveillance et détection des intrusions.

Solution retenue : Snort sur pfSense.

Objectif : détecter les attaques de type DDoS et brute force SSH.

SIEM (Security Information and Event Management) – centralisation et corrélation des logs.

Solution retenue : Splunk Enterprise.

Objectif : supervision, alertes en temps réel, visibilité SOC.

📄 Livrables produits

Rapport complet du projet (contexte, analyse des besoins, benchmarks, PoC, conclusions).

Procédures d’intégration :

WAF (ModSecurity)

IDS (Snort)

SIEM (Splunk)

Fiches réflexes (équipe IT & employés, inspirées des recommandations ANSSI).

Présentation PowerPoint pour la soutenance.
