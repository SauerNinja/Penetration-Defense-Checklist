![Penetration-Defense-Checklist](hero.png)

# Penetration-Defense-Checklist

A research article and interactive checklist based on thoughts by Setvin Noether (@SauerNinja), estimated at a 26-minute read.

Most penetration testing cheat sheets go stale within a year: the tools and CVEs listed age out, while the underlying attack surface keeps shifting toward identity, cloud metadata, edge appliances, and AI infrastructure. This project takes the opposite approach. Every item in the checklist starts from a documented, real-world attack pattern and ends at a concrete, checkable defensive control — sourced to a public framework (CISA KEV, MITRE D3FEND, MITRE ATT&CK, NIST CSF 2.0, OWASP) rather than a blog post or a stale wordlist.

The checklist covers the full lifecycle of a modern security assessment, written from a defensive posture throughout:

- **Pre-Engagement & Scope** — legal boundaries, rules of engagement, and third-party inventory
- **Reconnaissance & Attack Surface Mapping** — asset discovery, certificate transparency, secret scanning
- **Vulnerability Analysis & Web/API Hardening** — CISA KEV alignment, JWT/GraphQL hardening, supply-chain integrity
- **Critical Infrastructure & OT/ICS** — PLC isolation, Purdue Architecture segmentation, AWIA compliance
- **Identity & Active Directory Defense** — Kerberos hygiene, AD CS misconfiguration, tiered administration, MFA
- **Cloud, Container & Edge Infrastructure** — IMDSv2, rootless containers, edge-device lifecycle management
- **Post-Exploitation Detection & Lateral Movement** — process auditing, LOLBAS/GTFOBins detection, immutable logging
- **Defensive Tooling, Frameworks & Advisories** — CISA advisories, MITRE D3FEND, open-source blue-team tooling
- **Recent Incidents to Learn From** — 39 paraphrased, real-world incident lessons drawn from CSIS's Significant Cyber Incidents timeline, organized by category (ransomware, OT, identity, supply chain, cloud, aviation/logistics, nation-state espionage, hacktivism, financial, insider risk)

Each item ties back to a documented incident or an authoritative framework, so the reasoning behind every control is visible, not just the instruction. Checklist state persists locally in your browser, so you can work through it across multiple sessions and track completion as you harden an environment.

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
