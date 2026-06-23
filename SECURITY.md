# Security Policy

Vellixia takes security seriously. We appreciate coordinated disclosure of vulnerabilities.

## Supported versions

| Project | Supported |
|---|---|
| Latest release | ✅ |
| Previous release | ✅ for 90 days |
| Older versions | ❌ |

## Reporting a vulnerability

**Please do not file a public GitHub issue for security vulnerabilities.**

Email **[andresholivin01@gmail.com](mailto:andresholivin01@gmail.com)** with:

- Project name and version/commit
- A clear description of the vulnerability
- Reproduction steps or a proof-of-concept
- Potential impact and attack scenario
- Your name / handle (if you'd like to be credited)

We aim to:

- Acknowledge within **48 hours**
- Provide an initial assessment within **5 business days**
- Coordinate disclosure timing with you

## Scope

In scope:

- Code execution or sandbox escapes
- Authentication or authorization bypass
- Data exposure (memory contents, secrets, sync payloads)
- Cryptographic weaknesses
- Remote code execution via network inputs
- Dependency confusion / supply-chain compromise

Out of scope:

- Self-XSS
- Denial-of-service that requires local access
- Issues in third-party dependencies (report upstream)
- Theoretical issues without a realistic attack path

## Recognition

We credit reporters in release notes (unless you prefer to remain anonymous). Thank you for helping keep Vellixia — and its users — secure.