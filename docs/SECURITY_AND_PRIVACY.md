# Security and Privacy Principles

**Status:** Planning document. The initiative does not currently operate a secure network, browser, video platform, or dedicated security team.

Privacy and security should be built into future systems from the beginning. No service should be described as “fully private” or “secure” without a defined threat model, testing, and honest disclosure of limitations.

## Principles

1. **Minimize data.** Do not collect personal data unless a specific purpose requires it.
2. **Secure by default.** Use safe defaults, strong authentication, encryption in transit and at rest where appropriate, secure dependency management, and timely updates.
3. **Limit access.** Give people only the permissions they need; separate administrative roles and review privileged access.
4. **Protect dissent.** Do not expose members' beliefs, private activity, location, identity, or membership status without a legitimate, disclosed, lawful basis.
5. **Avoid unnecessary identity checks.** Do not demand passports, legal names, or biometrics simply to participate in public discussion.
6. **Separate public transparency from private data.** Publish decisions and aggregate information without doxxing members or disclosing sensitive reports.
7. **Plan for failure.** Define incident response, backups, recovery, data deletion, and notification procedures before running a service with real users.
8. **Do not promise absolute safety.** Describe threat models and residual risks honestly.

## Threat model questions

Before deploying any digital service, document:

- What assets are being protected?
- Who might attack or misuse the service?
- What are the likely capabilities and motivations of those actors?
- What happens if an account, administrator, device, or hosting provider is compromised?
- Which data is genuinely necessary to retain?
- How will abuse, account recovery, content moderation, and legal requests be handled?
- What harms could arise from false accusations or mistaken identity?
- How can users leave, export what they are entitled to, and request deletion where applicable?

## Member safety

- Do not publish member lists or private contact information by default.
- Do not encourage members to reveal sensitive information publicly.
- Do not direct members to confront, track, threaten, or retaliate against critics.
- Provide a confidential route for reporting serious safety concerns once an operating organization can support it.
- Do not imply that membership guarantees physical protection, legal assistance, employment, or anonymity.

## Security vulnerability reporting

Until a dedicated private vulnerability reporting channel is established, do not publish exploitable details or personal information in public issues. Contact the repository maintainer privately through GitHub and provide the minimum details needed to understand the issue. Do not expect 24/7 incident response at this early stage.

When software is developed, enable GitHub's private vulnerability reporting where available, maintain a dedicated `SECURITY.md`, track supported versions, and publish a coordinated disclosure policy.

## Future technical projects

Any proposed browser, video service, messaging network, operating system, or identity system should begin with a threat model, an abuse model, a privacy review, and a realistic maintenance plan. Prefer proven components where appropriate; do not roll custom cryptography. Security claims should be independently tested before being used in public marketing.
