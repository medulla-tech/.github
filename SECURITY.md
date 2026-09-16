# Politique de Sécurité et Divulgation des Vulnérabilités (Medulla)

La sécurité de la plateforme **Medulla** et des agents déployés chez nos clients est notre priorité. Conformément au règlement européen *Cyber Resilience Act* (CRA), ce document définit la politique de gestion, de tri et de divulgation des vulnérabilités appliquée par l'éditeur.

---

## 1. Versions Supportées

| Version | Statut du support | Correctifs de sécurité |
| :--- | :--- | :--- |
| **v5.6.x (Version actuelle)** | **Support actif** | ✅ Oui (Bugs et toutes vulnérabilités) |
| **v5.6.x-1 (Version N-1)** | **Support étendu** | ⚠️ Failles critiques uniquement (CVSS $\ge$ 7.0) |
| ** antérieur à v5.6.x-1** | **Fin de vie (EOL)** | ❌ Aucun (Mise à jour requise vers v5.6.4) |

---

## 2. Périmètre (Scope)

**Périmètre couvert :**
* L'**Agent Medulla** (services et exécutables Windows / Linux / macOS).
* Le **Serveur Medulla** (API, orchestration, console Web).
* Les **Installeurs et binaires officiels** produits et signés par NATSU.

**Périmètre exclu :**
* Les forks non officiels du code source.
* Les dépendances amont (Python, PHP, XMPP, Guacamole) hors de leur intégration dans nos builds officiels.
* Les infrastructures clientes gérées en propre.

---

## 3. Signalement d'une Vulnérabilité

> **IMPORTANT : Ne créez pas d'Issue publique sur GitHub pour signaler une vulnérabilité.**

Pour toute divulgation coordonnée (*Coordinated Vulnerability Disclosure*), contactez-nous de manière confidentielle :

* **Email dédié** : `security@medulla-tech.io`
* **Clé PGP publique** :
  * *Fingerprint* : `2C7F 8241 5E76 BE1A 242B E111 562F 02D5 1ABA EFC1`
  * *Lien direct* : `https://medulla-tech.io/.well-known/pgp-key.txt`

---

## 4. Engagements et Délais de Traitement (SLA)

* **Accusé de réception** : Sous **48 heures ouvrées**.
* **Qualification CVSS** : Sous **7 jours ouvrés**.
* **Correctif Critique (CVSS 9.0 – 10.0)** : Sous **7 jours ouvrés**.
* **Correctif Élevé (CVSS 7.0 – 8.9)** : Sous **15 jours ouvrés**.
* **Moyen / Faible (CVSS < 7.0)** : Intégration dans la prochaine version planifiée.

---

## 5. Divulgation Coordonnée

Nous demandons un embargo raisonnable avant toute publication externe. Nous créditons systématiquement les chercheurs dans nos *Release Notes* et *Security Advisories*.
