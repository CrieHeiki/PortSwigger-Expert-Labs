# PortSwigger Web Security Academy – Expert Labs

A technical research repository documenting my learning, analysis, and exploitation of Expert-level labs from [PortSwigger Web Security Academy](https://portswigger.net/web-security).

This repository focuses on understanding complex web application vulnerabilities, analyzing exploitation techniques, and documenting the underlying security mechanisms through hands-on practice.

Rather than focusing solely on payloads or step-by-step solutions, each writeup aims to explain the reasoning, attack surface, exploitation process, and root cause behind the vulnerability.

## Objectives

- Develop a deeper understanding of advanced web application vulnerabilities.
- Improve practical penetration testing and exploitation skills.
- Analyze complex attack scenarios and security mechanisms.
- Understand vulnerability root causes through technical investigation.
- Document reproducible findings and exploitation techniques.
- Build a structured technical knowledge base for future security research.

## Scope

This repository covers Expert-level labs across various web security topics, including:

- Access Control
- Authentication
- Business Logic Vulnerabilities
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Deserialization
- HTTP Request Smuggling
- Server-Side Request Forgery (SSRF)
- Server-Side Template Injection (SSTI)
- Web Cache Poisoning
- Web Cache Deception
- Other advanced web application vulnerabilities

The categories will be expanded as additional labs are completed and documented.

## Repository Structure

```text
PortSwigger-Expert-Labs/
│
├── README.md
│
├── Access-Control/
│   └── [lab-name]/
│       ├── README.md
│       └── evidence/
│
├── Authentication/
│
├── Deserialization/
│
├── HTTP-Request-Smuggling/
│
├── Server-Side/
│
├── Web-Cache/
│
└── templates/
    └── writeup-template.md
```

Each lab is documented independently in its corresponding directory.

## Writeup Methodology

Each writeup follows a structured technical analysis approach:

1. **Lab Overview** – Introduction, objectives, and vulnerability classification.
2. **Technical Background** – Relevant concepts, protocols, and security mechanisms.
3. **Reconnaissance & Attack Surface** – Application behavior, endpoints, and attack surface identification.
4. **Vulnerability Analysis** – Observations, hypotheses, and vulnerability validation.
5. **Exploitation Strategy** – Attack reasoning, constraints, and selected techniques.
6. **Exploitation Process** – Detailed exploitation stages with HTTP requests, responses, and analysis.
7. **Final Exploit** – Reproducible exploitation steps and verification.
8. **Root Cause Analysis** – Underlying implementation flaws and security assumptions.
9. **Impact & Mitigation** – Potential security impact and remediation recommendations.
10. **Key Takeaways & References** – Lessons learned and technical references.

## Tools & Technologies

Tools and technologies used throughout the research may include:

- Burp Suite Professional
- Browser Developer Tools
- cURL
- Python
- PHP
- Java
- Ruby
- Other testing and debugging utilities when required by a specific lab.

The tools used in each lab are documented individually.

## Lab Index

A centralized index of completed labs and their corresponding technical writeups.

| Category | Lab | Difficulty | Status |
|---|---|---|---|
| [Category] | [Lab Name](path/to/lab) | Expert | Solved |

This index is updated as new writeups are completed.

## Research Approach

My approach emphasizes understanding the underlying mechanisms rather than simply reproducing existing solutions.

Key areas of investigation include:

- Identifying trust boundaries and attack surfaces.
- Understanding how user-controlled input is processed.
- Analyzing application behavior through HTTP requests and responses.
- Investigating framework and library implementation details when relevant.
- Constructing and validating exploitation hypotheses.
- Examining failed exploitation attempts and their underlying causes.
- Evaluating root causes and appropriate remediation strategies.

## Disclaimer

This repository is intended for educational purposes, security research, and authorized security testing.

All practical exercises documented here are conducted within PortSwigger Web Security Academy labs or controlled environments.

The techniques described should only be applied to systems for which explicit authorization has been obtained.

## References

- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [PortSwigger Research](https://portswigger.net/research)
- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)
