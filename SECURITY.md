*Lisez ce document en [français](SECURITY.fr.md).*

# Security Policy and Vulnerability Disclosure (Medulla)

The security of the **Medulla** platform and the agents deployed at our clients is our priority. In accordance with the European regulation *Cyber Resilience Act* (CRA), this document defines the vulnerability management, triage, and disclosure policy applied by the editor.

---

## 1. Supported Versions

| Version | Support status | Security fixes |
| :--- | :--- | :--- |
| **v5.6.x (Current version)** | **Active support** | ✅ Yes (Bugs and all vulnerabilities) |
| **v5.6.x-1 (N-1 version)** | **Extended support** | ⚠️ Critical flaws only (CVSS $\ge$ 7.0) |
| **earlier than v5.6.x-1** | **End of Life (EOL)** | ❌ None (Update required to v5.6.4) |

---

## 2. Scope

**Covered scope:**
* The **Medulla Agent** (Windows / Linux / macOS services and executables).
* The **Medulla Server** (API, orchestration, Web console).
* The **Official installers and binaries** produced and signed by NATSU.

**Excluded scope:**
* Unofficial forks of the source code.
* Upstream dependencies (Python, PHP, XMPP, Guacamole) outside of their integration in our official builds.
* Client infrastructures managed in-house.

---

## 3. Vulnerability Reporting

> **IMPORTANT: Do not create a public Issue on GitHub to report a vulnerability.**

For any coordinated disclosure (*Coordinated Vulnerability Disclosure*), contact us confidentially:

* **Dedicated email**: `security@medulla-tech.io`
* **Public PGP key**:
  * *Fingerprint*: `2C7F 8241 5E76 BE1A 242B E111 562F 02D5 1ABA EFC1`
  * *Direct link*: `https://medulla-tech.io/.well-known/pgp-key.txt`

---

## 4. Commitments and Processing Deadlines (SLA)

* **Acknowledgment of receipt**: Within **48 business hours**.
* **CVSS Qualification**: Within **7 business days**.
* **Critical Fix (CVSS 9.0 – 10.0)**: Within **7 business days**.
* **High Fix (CVSS 7.0 – 8.9)**: Within **15 business days**.
* **Medium / Low (CVSS < 7.0)**: Integration in the next planned version.

---

## 5. Coordinated Disclosure

We request a reasonable embargo before any external publication. We systematically credit researchers in our *Release Notes* and *Security Advisories*.
