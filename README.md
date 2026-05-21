# Audit Tool Skills

> 20 skills les plus populaires pour la creation d'un outil d'audit web, securite, performance et qualite du code.
>
> ## Structure du projet
>
> ```
> audit-tool-skills/
>   audit_skills.json   # Les 20 skills en format JSON
>   README.md           # Documentation
> ```
>
> ## Les 20 Skills par Categorie
>
> ### Securite (6 skills)
> | # | Skill | Priorite | Outils |
> |---|-------|----------|--------|
> | 1 | Security Vulnerability Assessment | CRITICAL | OWASP ZAP, Snyk, SonarQube |
> | 6 | Dependency & Package Audit | CRITICAL | npm audit, Snyk, OWASP Dependency-Check |
> | 7 | API Security Testing | CRITICAL | Postman, OWASP ZAP, Burp Suite |
> | 9 | SSL/TLS Certificate Analysis | HIGH | SSL Labs, testssl.sh, OpenSSL |
> | 16 | Content Security Policy (CSP) | HIGH | securityheaders.com, Mozilla Observatory |
> | - | GDPR / Data Privacy Compliance | CRITICAL | OneTrust, TrustArc |
>
> ### Infrastructure (3 skills)
> | # | Skill | Priorite | Outils |
> |---|-------|----------|--------|
> | 8 | Infrastructure & Cloud Security | CRITICAL | Prowler, ScoutSuite, Checkov |
> | 17 | Docker & Container Security | HIGH | Trivy, Anchore, Docker Bench |
> | 19 | Network & Port Scanning | MEDIUM | Nmap, Nessus, Masscan |
>
> ### Performance & Qualite (4 skills)
> | # | Skill | Priorite | Outils |
> |---|-------|----------|--------|
> | 2 | Performance Profiling | HIGH | Lighthouse, WebPageTest, Chrome DevTools |
> | 3 | SEO Analysis | HIGH | Screaming Frog, Ahrefs, Google Search Console |
> | 5 | Code Quality & Static Analysis | HIGH | SonarQube, ESLint, CodeClimate |
> | 15 | Automated Testing Coverage | HIGH | Jest, Istanbul, SonarQube Coverage |
>
> ### Accessibilite & UX (3 skills)
> | # | Skill | Priorite | Outils |
> |---|-------|----------|--------|
> | 4 | Accessibility Compliance (WCAG) | HIGH | axe, WAVE, Lighthouse |
> | 10 | Mobile Responsiveness | MEDIUM | BrowserStack, Chrome DevTools |
> | 20 | UX / Usability Heuristics | MEDIUM | Hotjar, FullStory, UserTesting |
>
> ### DevOps & Monitoring (4 skills)
> | # | Skill | Priorite | Outils |
> |---|-------|----------|--------|
> | 11 | Database Performance & Security | HIGH | pgBadger, MySQL Explain |
> | 12 | Log Analysis & Monitoring | MEDIUM | ELK Stack, Splunk, Datadog |
> | 14 | Cross-Browser Compatibility | MEDIUM | BrowserStack, Sauce Labs |
> | 18 | CI/CD Pipeline Audit | HIGH | GitGuardian, TruffleHog |
>
> ## Distribution des priorites
>
> - **CRITICAL** : 5 skills
> - - **HIGH** : 11 skills
>   - - **MEDIUM** : 4 skills
>    
>     - ## Utilisation avec Claude Code
>    
>     - ```bash
>       git clone https://github.com/youri34500/audit-tool-skills.git
>       cd audit-tool-skills
>       ```
>
> Puis dans Claude Code :
> ```
> Utilise audit_skills.json pour construire un outil d'audit complet.
> ```
>
> ## Licence
>
> MIT
