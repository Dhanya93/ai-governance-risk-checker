# ai-governance-risk-checker
AI Governance Risk Checker

A free, interactive web-based tool for assessing AI governance maturity across six risk domains — no login, no signup, no friction. Built for security practitioners, GRC analysts, and organisations deploying AI systems who want a practical, framework-mapped starting point for understanding their governance gaps.

Live tool: dhanya93.github.io/ai-governance-risk-checker


# What It Does

Users select one or more risk domains, answer 10 questions per domain, and receive a scored output including:


An overall AI Governance Maturity Score — Foundational, Developing, Managed, or Advanced
A domain-by-domain risk score with visual severity indicators
A prioritised list of findings mapped to specific framework controls
Actionable context for each finding explaining why it matters



# Six Assessment Modules

ModuleQuestionsFocusAI IAM & Access Control10Autonomous access decisions, prompt injection, privilege escalation, audit trailsAI Data Governance & Privacy10Training data inventory, PIPEDA compliance, data minimisation, breach responseAI Model Risk & Lifecycle10Model validation, drift monitoring, adversarial testing, model inventoryAI Vendor & Third-Party Risk10Vendor due diligence, contractual controls, supply chain risk, exit strategyAI Incident Response Readiness10AI-specific IR playbooks, detection capability, rollback, regulatory notificationRegulatory Compliance Readiness10EU AI Act classification, OSFI B-13, PIPEDA, ISO 42001, conformity assessments

Users can take a single module (approximately 5 minutes) or complete the full assessment across all six domains (approximately 10-15 minutes).


# Frameworks Referenced

Every finding in the tool is mapped to at least one of the following frameworks:


NIST AI Risk Management Framework (AI RMF 1.0)
OWASP LLM Top 10
ISO/IEC 27001:2022
NIST SP 800-53 Rev 5
EU AI Act (Regulation 2024/1689)
OSFI B-13 — Technology and Cyber Risk Management
PIPEDA — Personal Information Protection and Electronic Documents Act
ISO 42001 — AI Management Systems



# Canadian Regulatory Context

The tool has been designed with Canadian financial services organisations in mind, with explicit coverage of:


OSFI B-13 obligations across technology risk, model risk, and third-party AI oversight
PIPEDA requirements for AI systems processing personal data
Provincial privacy law considerations
FINTRAC relevance for AI-assisted transaction monitoring


This does not make the tool Canada-only — the framework references and risk findings apply globally. The Canadian regulatory layer is additive for organisations operating under those obligations.


# Technical Details

The tool is a single self-contained HTML file with no external dependencies beyond Google Fonts. It runs entirely in the browser with no data collection, no backend, and no cookies beyond session state.


No personal data is collected
No answers are transmitted or stored
Results exist only in the user's browser session
The tool works offline once the page is loaded


To self-host: download index.html and open it in any modern browser, or deploy to any static hosting service.


# Limitations and Scope

This tool is designed as a structured starting point for AI governance assessment — not a comprehensive audit or regulatory compliance certification.


Questions are representative, not exhaustive
Findings identify areas for investigation, not confirmed control failures
Framework references point to relevant controls but do not constitute a complete control mapping
The tool does not replace professional GRC assessment, legal advice, or regulatory examination


Results should be used to prioritise further investigation and remediation planning, not as a definitive compliance determination.




# References


NIST AI RMF 1.0: https://www.nist.gov/artificial-intelligence/ai-rmf
OWASP LLM Top 10: https://owasp.org/www-project-top-10-for-large-language-model-applications/
ISO/IEC 27001:2022: https://www.iso.org/standard/27001
NIST SP 800-53 Rev 5: https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final
EU AI Act: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R1689
OSFI B-13: https://www.osfi-bsif.gc.ca/en/guidance/guidance-library/technology-cyber-risk-management
PIPEDA: https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/pipeda/
ISO 42001: https://www.iso.org/standard/81230.html



# Author

Dhanya Mary Sam
AI Analyst and GRC Practitioner
Greater Toronto Area, Canada

Certifications: CEH v13 | Security+ (In Progress)
Currently pursuing: CompTIA SecAI+ | ISO 27001 Foundation | ISO 42001 Foundation

LinkedIn: https://www.linkedin.com/in/dhanya-m-sam
GitHub: https://github.com/Dhanya93


This tool was built for educational and professional development purposes. It does not constitute legal, regulatory, or professional advice. Framework references are illustrative and do not represent an exhaustive control mapping.
