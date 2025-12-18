# CS-305-14563-M01-Software-Security
1) Client summary + software requirements

The client was Artemis Financial, a financial services company that needed to improve the security of a Java-based web application used to exchange and protect sensitive data. The primary issue they wanted addressed was software security risk—specifically identifying known vulnerabilities in third-party dependencies and improving the application’s ability to protect data confidentiality and integrity (for example, through secure communication and stronger security practices).

2) What I did well + why secure coding matters

I did well at systematically identifying vulnerabilities using automated scanning and then analyzing results to separate true risks from false positives. Secure coding is important because vulnerabilities can lead to data breaches, service disruptions, legal/regulatory exposure, and loss of customer trust. Strong software security increases a company’s overall well-being by reducing operational risk, improving reliability, and protecting both customer data and business continuity.

3) Challenging/helpful part of the vulnerability assessment

The most challenging (and helpful) part was validating findings—understanding severity, whether a vulnerability was actually reachable/exploitable in the application, and determining the best remediation path. This step matters because “fix everything immediately” isn’t realistic; you need to prioritize based on risk and impact.

4) Increasing layers of security + future approach

I increased layers of security by combining dependency vulnerability management (identifying and updating vulnerable libraries) with secure configuration and secure coding best practices (defense-in-depth). In the future, I would assess vulnerabilities using tools such as OWASP Dependency-Check, static analysis tools, code reviews, and threat modeling. To choose mitigations, I would use a risk-based approach (severity, exploitability, exposure, business impact) and apply the most effective controls (upgrade, patch, configuration hardening, input validation, secure defaults, and monitoring).

5) Ensuring the application stayed functional and secure

To ensure the application remained functional and secure, I used a combination of build verification, testing, and re-scanning after refactoring. After making changes (like updating dependencies or refactoring security-related code), I checked for new issues by rebuilding the project, running available tests, and generating a new vulnerability report to confirm vulnerabilities were reduced and that no new vulnerabilities were introduced.

6) Resources, tools, and practices used

Resources and tools that will help me in future tasks include:
- OWASP Dependency-Check for identifying vulnerable third-party libraries
- Reviewing CVE information to understand real-world impact
- Secure coding practices (input validation, least privilege mindset, secure configuration)
- A repeatable workflow: scan → analyze → remediate → rebuild/test → rescan

7) What I would show employers

For future employers, I would show the completed vulnerability assessment or secure software practices report, along with evidence of my secure development workflow (before/after scan results, documented remediation decisions, and the updated codebase). This demonstrates practical skills in identifying vulnerabilities, prioritizing risk, implementing fixes, and verifying security improvements without breaking functionality.
