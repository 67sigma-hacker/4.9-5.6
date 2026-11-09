Security+ Study Lab — Objectives 4.9 & 5.6
A no-sign-up, offline-friendly interactive study website for CompTIA Security+ SY0-701 topics:
- 4.9 — Data Sources: investigation evidence, log sources, Windows Event ID 4625, Linux authentication logs, SIEM, aggregation vs. correlation, NetFlow vs. PCAP, metadata, vulnerability scans, automated reports, dashboards, and supplemental telemetry terms.
- 5.6 — Security Awareness: phishing awareness, BEC, pretexting, watering-hole attacks, baiting, spear phishing, whaling, vishing, smishing, physical threat vectors, AI-driven deception, misinformation/disinformation, and safe reporting/verification habits.
Run it
1. Download and extract the ZIP.
2. Open index.html in a modern browser (Chrome, Edge, Firefox, or Safari).
3. No account, server, package install, or external JavaScript library is required.
The course uses local browser storage only for completion progress. The focus clock and quiz timer run in the open page. Read-aloud uses your browser's built-in speech synthesis if available.
Publish with GitHub Pages
The GitHub connection available in the workspace can work with files in existing repositories, but it does not expose an action to create a brand-new repository or enable GitHub Pages. To publish this as a new public repo:
1. On GitHub, create a new public repository named securityplus-study-lab (do not add a README or license during creation, since this folder already has them).
2. Upload the contents of this folder to the repository root. Make sure index.html, styles.css, and app.js are at the top level.
3. Open Settings → Pages. Under Build and deployment, select Deploy from a branch, choose main and / (root), then Save.
4. After GitHub Pages finishes its first deployment, the site address will be https://YOUR-USERNAME.github.io/securityplus-study-lab/.
GitHub may take a short time to deploy after the Pages setting is saved. The address above is the expected pattern, not a claim that the site has already been published.
Source and accuracy notes
- The three user-provided class PDFs are the main lesson source. The website preserves the teacher's core examples and vocabulary.
- The published CompTIA Security+ SY0-701 exam-objective document is used to cross-check the objective names and scope. The official 4.9 outline includes vulnerability scans, automated reports, dashboards, packet captures, firewall/application/endpoint/OS security/IDS-IPS/network logs, and metadata. The official 5.6 outline includes phishing awareness, anomalous behavior recognition, user guidance and training, situational awareness, insider threats, password management, removable media/cables, social engineering, operational security, hybrid/remote work, reporting/monitoring, and awareness-program development/execution.
- Syslog/514, NetFlow, CVE/OSINT/threat feeds, deepfake audio, badge skimming, and some attack examples are marked as class extensions or supplementary detail where appropriate.
- Your private CertMaster account/course is not accessible from this project. This site does not copy CertMaster content, official exam questions, or brain dumps. All quiz questions are original practice questions written for this study lab.
- A packet capture does not decrypt encrypted traffic by itself. Plaintext exposure depends on the protocol and its configuration. The SMTP plaintext example in the class slides should be understood in an unencrypted context.
- SIEM is described as a central platform for ingestion, parsing, alerting, and correlation—not as one individual log type.
Files
- index.html — site structure and content
- styles.css — responsive dark cyber-themed interface
- app.js — navigation, progress, focus timer, simulations, flashcards, and original 20-question test
- SOURCES.md — source map and scope notes
