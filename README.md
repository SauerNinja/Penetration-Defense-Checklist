![Penetration-Defense-Checklist](hero.png)

# Penetration-Defense-Checklist

A research article and interactive checklist, estimated at a 116-minute read.

American infrastructure and companies are under sustained attack from foreign state-linked hackers — telecoms, water utilities, energy grids, hospitals, and companies of every size. Most penetration testing cheat sheets go stale within a year: the tools and CVEs listed age out, while the underlying attack surface keeps shifting toward identity, cloud metadata, edge appliances, and AI infrastructure. This project takes the opposite approach. Every item in the checklist starts from a documented, real-world attack pattern and ends at a concrete, checkable defensive control — sourced to a public framework (CISA KEV, MITRE D3FEND, MITRE ATT&CK, NIST CSF 2.0, OWASP, NIST SP 800-series, and more) rather than a blog post or a stale wordlist.

The checklist covers the full lifecycle of a modern security program across 23 sections, written from a defensive posture throughout:

- **Pre-Engagement & Scope** — legal boundaries, rules of engagement, third-party inventory, insurance obligations
- **Reconnaissance & Attack Surface Mapping** — asset discovery, certificate transparency, secret scanning, OSINT self-audit
- **Vulnerability Analysis & Web/API Hardening** — CISA KEV alignment, JWT/GraphQL hardening, SSRF, request smuggling, secure SDLC
- **Critical Infrastructure & OT/ICS** — PLC isolation, Purdue Architecture segmentation, AWIA compliance, CISA ICS advisories
- **Identity & Active Directory Defense** — Kerberos hygiene, AD CS misconfiguration, tiered administration, MFA, DCSync auditing
- **Cloud, Container & Edge Infrastructure** — IMDSv2, rootless containers, edge-device lifecycle management, Kubernetes RBAC
- **Post-Exploitation Detection & Lateral Movement** — process auditing, LOLBAS/GTFOBins detection, canary accounts, immutable logging
- **Defensive Tooling, Frameworks & Advisories** — CISA advisories, MITRE D3FEND, EPSS, threat intelligence feeds, open-source SIEM
- **Defending U.S. Infrastructure & Companies From Foreign Hacking** — 39 real, paraphrased incidents from CSIS's timeline, each mapped to a specific control
- **Social Engineering & Phishing Defense** — simulations, out-of-band verification, deepfake awareness, lookalike-domain monitoring
- **Mobile Device & BYOD Security** — MDM enforcement, containerization, remote wipe, hardened travel devices
- **Physical Security & Facility Access** — badge-log auditing, network jack lockdown, visitor escort policy, document destruction
- **Third-Party & Supply Chain Risk Management** — vendor inventory, SOC 2/ISO 27001 review, breach-notification testing, SBOM requirements
- **Email & Communications Security** — SPF/DKIM/DMARC enforcement, sandboxing, MTA-STS, DMARC monitoring
- **Data Classification & Encryption** — classification scheme, customer-managed keys, TLS hardening, classification-aware DLP, retention policy
- **Zero Trust Network Access & Passwordless Authentication** — ZTNA, FIDO2 passkeys, device posture checks, just-in-time access
- **Wireless Network & RF Security** — WPA3-Enterprise, guest segmentation, rogue AP detection, evil-twin monitoring
- **Secrets, Configuration & Change Management** — secrets managers, container image scanning, security headers, patch SLAs, config-drift detection
- **Insider Threat & Personnel Security** — background checks, same-day offboarding, privileged-user monitoring, access reviews, confidential reporting
- **Regulatory Compliance Mapping** — HIPAA, PCI DSS, GDPR/CCPA, SOX control mapping
- **Business Continuity & Disaster Recovery** — RTO/RPO definitions, DR failover testing, alternate communications, manual fallback procedures, BIA review
- **Incident & Crisis Management** — severity tiers, Incident Commander authority, RACI matrix, crisis communications by audience, legal/law enforcement contacts, blameless post-incident review
- **Nation-State Threat Actor Profiles** — China, Russia, Iran, and North Korea's named threat groups, their distinct tactics, and the specific tricks to watch for from each

Every one of the 233+ checklist items includes a plain-language Summary and a concrete real-world Example alongside the technical description. Checklist state persists locally in your browser, so you can work through it across multiple sessions and track completion as you harden an environment.

## Files

- `index.html` — the full interactive checklist page
- `hero.png` — hero artwork
- `og-image.png` — social share image
- `favicon.ico`, `favicon-16.png`, `favicon-32.png`, `apple-touch-icon.png`, `icon-512.png` — favicon set
- `sitemap.xml`, `robots.txt` — search engine infrastructure
- `404.html` — themed error page
- `LICENSE` — MIT License

## License

MIT License — see [LICENSE](LICENSE) for details.

A research article based on thoughts by Setvin Noether (@SauerNinja).
