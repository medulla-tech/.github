[English](README.md) | [Français](README.fr.md)

# Medulla RMM

Medulla RMM est une plateforme open source d’automatisation IT et de gestion du cycle de vie des postes de travail, conçue pour automatiser les tâches répétitives, déployer applications et systèmes d’exploitation à grande échelle et administrer de façon proactive des environnements IT distribués.

Conçu pour les équipes IT modernes, Medulla assure une gestion en temps réel des infrastructures complexes, distribuées, hybrides et distantes, grâce à Python 3 et à des communications basées sur XMPP.

## Pourquoi Medulla ?

Medulla aide les équipes IT à simplifier la gestion des postes de travail en réunissant au sein d’une même plateforme l’automatisation, le déploiement, l’inventaire, la gestion des mises à jour, la prise en main à distance et la gouvernance.

Pensé pour les organisations qui gèrent des infrastructures distribuées, Medulla permet aux administrateurs IT de :

- Automatiser les opérations répétitives
- Déployer systèmes d’exploitation et logiciels à grande échelle
- Maintenir une visibilité temps réel sur le parc
- Gouverner de façon sécurisée les environnements distribués
- Réduire la complexité opérationnelle et le coût total de possession

---

## Clients pris en charge

- Windows 10 et versions ultérieures (y compris LTSC)
- Debian 12 (Bookworm)
- Ubuntu
- Zorin OS
- macOS 26.2 ou ultérieur
- Smartphones et tablettes Android (via le module MDM)

**Prise en charge à venir :** Debian 13.

## Serveur supporté

- Debian 12 (Bookworm)

Consultez la documentation pour les prérequis minimaux :
https://docs.medulla-tech.io/books/installation-medulla/page/etape-1-installation-os-debian-pour-serveur-medulla


---

## Architecture technique

Medulla s’appuie sur une architecture distribuée reposant sur :

- Services backend en Python 3
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
- Ciblage par groupes
- Gestion du cycle de vie logiciel

### Inventaire & Visibilité temps réel

- Inventaire matériel et logiciel temps réel (via XMPP)
- Visibilité des postes en ligne / hors ligne / itinérants
- Scan réseau et découverte d’équipements
- Groupes dynamiques auto-alimentés
- Intégration native avec GLPI

### Prise en main à distance

- SSH, RDP et VNC via Apache Guacamole
- Accès distant chiffré, sans VPN
- Journalisation des sessions et piste d’audit
- Accès sécurisé aux postes distants et itinérants

### Sauvegarde & Restauration

- Sauvegarde au niveau fichier (profils et données métiers)
- Remise en service rapide des postes
- Restauration accélérée des postes de travail

### Gestion des mises à jour (alternative WSUS)

- Mises à jour pilotées par règles, par groupe de postes
- Tableau de bord de conformité temps réel
- Pilotage des mises à jour Windows
- Mises à jour des paquets Linux, approuvées par règle
- Optimisation de la bande passante

### Supervision par sondes (Reflex)

- Sondes posées sur une machine, un groupe, une entité ou tout le parc
- Fréquence de mesure à partir de cinq minutes
- Seuils différents selon l'entité, sur une même sonde
- 24 sondes livrées : sécurité, système, stockage, service et application
- Sondes personnelles (sh sous Linux et macOS, PowerShell sous Windows)
- Suivi, acquittement et historique des alertes
- Courbes de mesures, machine par machine
- Notifications par courriel
- Linux, Windows et macOS

### Kiosque applicatif

- Catalogue applicatif piloté par l’IT
- Applications par rôle ou groupe
- Applications pré-packagées
- Intégration automatique dans la conformité

### Gestion des terminaux mobiles (MDM)

- Gestion des smartphones et tablettes Android, basée sur la solution open source Headwind MDM
- Enrôlement par QR code ou lien d'inscription
- Déploiement d'applications et de fichiers
- Politiques de sécurité : mode kiosque, restrictions réseau, verrouillage
- Commandes à distance, messages et prise en main de l'écran

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
- Capacités supplémentaires de conformité des postes
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
monitoring
mdm
```
