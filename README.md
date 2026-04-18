# 2L IoT-Compliance Sentinel: The Engineering Audit Engine

<img src="assets/Screenshot 1.png" alt="App Screenshot" width="1000">

**Audit Smarter. Deploy Faster. Stay Compliant.**

Navigating IoT security standards like **ETSI EN 303 645** and **NISTIR 8259A** is often a manual, fragmented nightmare. The **2L IoT-Compliance Sentinel** is a professional-grade, "Single-File" expert system designed to bridge the gap between complex legal requirements and technical hardware implementation.

Built on the **IBM Carbon Design System**, the Sentinel provides an interactive, logic-driven audit interface that generates "Auditor-Ready" compliance reports without ever sending your sensitive data to the cloud.

<img src="assets/Screenshot 2.png" alt="App Screenshot" width="1000">

---

## Core Pillars of the Sentinel

### 1. Total Data Sovereignty (Zero-Footprint)
Unlike SaaS-based audit platforms, the Sentinel operates as a standalone workstation.
* **No Database Required:** The entire engine runs locally in your browser.
* **100% Offline-Capable:** Sensitive project data never leaves your local machine, ensuring IPC and trade secret protection.
* **Zero Installation:** No `npm install`, no servers, and no dependencies. Just open the `.html` file and begin.

### 2. The "Dual-Core" Logic Engine
The tool utilizes a unified database where global standards overlap, allowing for simultaneous multi-standard auditing.
* **Global Mapping:** Checking a requirement in the ETSI view (e.g., No Default Passwords) automatically updates the mathematically equivalent NIST requirement.
* **Evidence Vault:** Every requirement includes a dedicated field for technical evidence, Git commit hashes, and implementation notes.
* **Smart Persistence:** Every interaction is instantly saved to `localStorage` via **Reactive State Hydration**, ensuring zero data loss if a session is interrupted.

<img src="assets/Screenshot 3.png" alt="App Screenshot" width="1000">

### 3. Executive-Grade Reporting
Transform technical audits into boardroom-ready documentation in seconds.
* **Compliance Pulse:** A high-level visual summary of Pass/Fail/NA status across all 13 security domains (Passwords, Updates, Attack Surface, etc.).
* **PDF Generation:** Uses a client-side engine to map your audit state into a professional **Statement of Conformity** featuring 2L Tech Dynamics branding.
* **JSON Portability:** Export your entire audit as a `.json` file to resume sessions on different machines or archive project snapshots.

---

<img src="assets/Screenshot 4.png" alt="App Screenshot" width="1000">

## Technical Architecture & Stack

* **Framework Coverage:** Optimized for NISTIR 8259A (USA) and ETSI EN 303 645 (EU/Global) regulatory alignment.
* **Visual Identity:** Built with the **IBM Carbon Gray 100** theme for a high-contrast, professional-grade dark mode.
* **Typography:** Utilizes **IBM Plex Sans** for interface clarity and **IBM Plex Mono** for high-density technical data and evidence logs.
* **Core Engine:** A serverless, Vanilla JS / ES6+ Single-Page Application (SPA) contained within a single file.
* **Data Persistence:** Local-first architecture using Browser LocalStorage combined with secure JSON export/import functionality.
* **Asset Integrity:** All icons and logos are implemented as **Base64-embedded SVGs** to ensure 100% functionality in offline or air-gapped environments.

---

<img src="assets/Screenshot 5.png" alt="App Screenshot" width="1000">

## Included in the Compliance Kit

* **The Sentinel App:** `2L_IoT_Compliance_v1.0.html` — The executable engine.
* **The Quick-Start Guide:** Technical documentation and regulatory references.
* **Template Library:** Sample JSON files to jumpstart your first audit.
* **Security Policy Templates:** Editable templates for corporate vulnerability disclosure policies.

---

<img src="assets/Screenshot 6.png" alt="App Screenshot" width="1000">

## Legal & Safety
**Disclaimer:** 2L IoT-Compliance is a self-assessment tool designed for guidance only. Use of this tool does not guarantee official certification by regulatory bodies. 2L Tech Dynamics is not liable for regulatory fines or security breaches.

*© 2026 2L Tech Dynamics. All Rights Reserved.*
