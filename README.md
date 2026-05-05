# Academic Project Work: Comparative Analysis of Docker and Podman Vulnerabilities
**University of Pisa | 1st Level Professional Master in Cybersecurity (Edition 2024/2025)**

# Project Work Accademico: Analisi comparativa delle vulunerabilità di Docker e Podman
**Università di Pisa | Master di I Livello in Cybersecurity (Edizione 2024/2025)**

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Podman](https://img.shields.io/badge/podman-%23892CA0.svg?style=for-the-badge&logo=podman&logoColor=white)
![Cybersecurity](https://img.shields.io/badge/security-shield?style=for-the-badge&color=red)
![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)

🇬🇧 **[English Version](#english)** | 🇮🇹 **[Versione Italiana](#italiano)**

---

<a name="english"></a>
## 🇬🇧 English

### About the Project
This repository contains the final PDF of my final Project Work for the Master in Cybersecurity written in LaTeX. AVAILABLE IN ITALIAN ONLY.

The thesis explores the isolation mechanisms and intrinsic vulnerabilities of two of the most widely used container engines: **Docker** and **Podman**. Through a methodical study of historical **CVEs** (Common Vulnerabilities and Exposures), the research demonstrates how architectural design choices do not just dictate operational features, but directly shape the attack surface.

### Core Topics
*   **Container Security:** Kernel primitives (Namespaces, cgroups, Capabilities, Seccomp).
*   **Docker Architecture:** Analysis of the monolithic *client-server* and *rootful* model, with a focus on `dockerd` vulnerabilities (e.g., API exposure, `runc` Container Escapes).
*   **Podman Architecture:** Exploring the *daemonless* and *rootless* paradigm via User Namespaces, and the complexity-induced vulnerabilities (e.g., Symlink Traversal, Race Conditions).
*   **Threat Modeling & Comparative Analysis:** A post-exploitation impact assessment evaluating the trade-off between total Privilege Escalation (Docker) and Denial of Service/Resource Exhaustion (Podman).



---

<a name="italiano"></a>
## 🇮🇹 Italiano

### Descrizione del Progetto
Questa repository contiene il PDF finale del mio Project Work redatto in LaTeX per il conseguimento del Master di I Livello in Cybersecurity.

La tesi esplora in profondità i meccanismi di isolamento e le vulnerabilità intrinseche di **Docker** e **Podman**. Attraverso lo studio metodico e comparato delle storiche **CVE** (Common Vulnerabilities and Exposures), la ricerca dimostra come il design architetturale di un software non determini solamente le sue funzionalità operative, ma plasmi e indirizzi direttamente le strategie offensive degli attaccanti.

### Temi Principali
*   **Sicurezza dei Container:** Studio delle primitive del kernel Linux (Namespace, cgroups, Capability, Seccomp).
*   **Ecosistema Docker:** Analisi del modello monolitico *client-server* e *rootful*, con focus sull'abuso del demone centrale `dockerd` e vulnerabilità di Container Escape.
*   **Ecosistema Podman:** Esplorazione del paradigma *daemonless* e *rootless* tramite User Namespace, e l'analisi dei nuovi vettori d'attacco legati alla complessità architetturale (es. Symlink Traversal, Race Condition e vulnerabilità TOCTOU).
*   **Threat Modeling e Analisi Comparata:** Valutazione dell'impatto post-compromissione, analizzando il *trade-off* tra il rischio di Privilege Escalation globale (Docker) e la vulnerabilità al Denial of Service computazionale (Podman).

