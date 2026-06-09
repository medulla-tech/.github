[English](README.md) | [Français](README.fr.md)

# Medulla RMM

Medulla est une plateforme open source de gestion unifiée des postes de travail (RMM) conçue pour automatiser les opérations IT, industrialiser les déploiements et administrer des environnements distribués en temps réel.

Conçu pour les équipes IT modernes, Medulla permet de piloter les postes de travail, serveurs et équipements distribués avec réactivité, sécurité et sans dépendance à un éditeur propriétaire.

Basé sur Python 3 et des communications temps réel via XMPP, Medulla fournit une visibilité instantanée et une automatisation avancée des opérations IT.

## Pourquoi Medulla ?

Medulla aide les équipes IT à simplifier la gestion des postes de travail en réunissant au sein d’une même plateforme :

- Le déploiement de systèmes et d’applications
- L’automatisation des tâches IT
- L’inventaire matériel et logiciel temps réel
- La gestion des mises à jour
- La prise en main à distance
- La conformité et la remédiation
- La gouvernance multi-sites et multi-entités

Pensé pour les environnements distribués, Medulla permet de :

- Automatiser les opérations répétitives
- Déployer rapidement systèmes et logiciels
- Maintenir une visibilité temps réel sur le parc
- Sécuriser la gestion des postes distants
- Réduire la complexité opérationnelle et les coûts IT

---

## Postes clients supportés

- Windows 10 et versions ultérieures (y compris LTSC)
- Debian 12 (Bookworm)
- Ubuntu
- Zorin OS

**Support à venir :** Debian 13 et agent Android.

## Serveur supporté

- Debian 12 (Bookworm)

Consultez la documentation pour les prérequis minimaux :
https://docs.medulla-tech.io/books/installation-medulla/page/etape-1-installation-os-debian-pour-serveur-medulla


---

## Architecture technique

Medulla s’appuie sur une architecture distribuée reposant sur :

- Python 3
- Communications temps réel via XMPP
- Gestion des endpoints par agent
- Infrastructure PXE pour la masterisation
- Apache Guacamole pour la prise en main distante
- LDAP / Active Directory
- Authentification OIDC

---

## Fonctionnalités principales

### Masterisation & Déploiement système

- Boot PXE
- Déploiement multicast
- Générateur de configuration système
- Extraction et réinjection de pilotes
- Déploiement bare-metal

### Télédéploiement & Gestion logicielle

- Assistant de packaging automatique
- Gestion de conformité
- Remédiation automatisée
- Scan CVE
- Déploiements planifiés
- Ciblage par groupes dynamiques
- Gestion du cycle de vie logiciel

### Inventaire & Visibilité temps réel

- Inventaire matériel et logiciel temps réel
- Visibilité des postes en ligne / hors ligne / itinérants
- Scan réseau et découverte d’équipements
- Groupes dynamiques auto-alimentés
- Intégration native avec GLPI

### Prise en main à distance

- SSH, RDP et VNC via Apache Guacamole
- Accès distant sécurisé sans VPN
- Journalisation des sessions
- Audit des actions administrateur

### Sauvegarde & Restauration

- Sauvegarde des profils utilisateurs et données métiers
- Restauration accélérée des postes
- Reprise rapide d’activité

### Gestion des mises à jour (alternative WSUS)

- Gouvernance des mises à jour par groupes
- Tableau de bord de conformité temps réel
- Optimisation de la bande passante
- Pilotage des mises à jour Windows

### Kiosque applicatif

- Catalogue applicatif piloté par l’IT
- Applications par rôle ou groupe
- Applications pré-packagées
- Intégration automatique dans la conformité

### Télétravail sécurisé

- Tunnels chiffrés natifs
- Aucun VPN d’entreprise nécessaire
- Continuité de gouvernance des postes distants

### Gouvernance N-Tiers

- Délégation multi-niveaux (site, BU, client, pays)
- Permissions fines par périmètre
- Audit complet des actions
- Multi-tenant (compatible MSP)

### Authentification & Intégrations

- LDAP / Active Directory
- OIDC
- Intégration native GLPI (On-Premise)

---

## Démarrage rapide

Vous souhaitez tester Medulla ?

Nous proposons une version installable de Medulla permettant d’évaluer la solution directement dans votre environnement.

### Prérequis minimaux

- Debian 12 (Bookworm)
- 8 vCPU minimum
- 16 Go de RAM minimum
- Connectivité réseau pour les communications XMPP

### Installation

Demandez le package d’installation et le guide de déploiement ici :

https://medulla-tech.io/testez-medulla/

Pour consulter la documentation complète d’installation et de déploiement :

https://docs.medulla-tech.io/books/installation-medulla

Notre équipe reste disponible pour toute question technique ou demande de démonstration.

---

## Documentation

Consultez la documentation complète :

https://docs.medulla-tech.io/

---

## Roadmap

Fonctionnalités à venir :

- Support Debian 13
- Agent Android
- Capacités de conformité avancées
- Automatisations étendues

---

## Licence

Medulla est distribué sous licence GPL.

Des contrats de support commercial sont disponibles pour les organisations souhaitant bénéficier de :

- Support technique
- Correctifs de sécurité
- Flux CVE
- Services de remplacement WSUS
- Services de dépôt et Store applicatif

---

## Communauté & Support

Une question, une idée ou un besoin ?

Ouvrez une issue GitHub ou contactez notre équipe.

Site web : https://medulla-tech.io/

---

## Tags GitHub

```txt
rmm
endpoint-management
it-automation
python
windows
linux
security
sysadmin
inventory
remote-management
patch-management
deployment
cve
open-source
xmpp
```
