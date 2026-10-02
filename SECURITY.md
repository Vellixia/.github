# Security Policy

Cunilab welcomes responsible disclosure of security vulnerabilities.

## Supported code

Support differs by project and maturity level.

Unless a repository states otherwise, security fixes are focused on the latest actively maintained release or default branch. Experimental, archived, or older versions may not receive fixes.

Check the affected repository for project-specific support information.

## Reporting a vulnerability

**Do not open a public GitHub issue for a suspected security vulnerability.**

Email **[andresholivin01@gmail.com](mailto:andresholivin01@gmail.com)** with enough information to investigate:

- affected project
- version, release, or commit
- vulnerability description
- reproduction steps or proof of concept
- potential impact
- relevant logs, traces, or screenshots
- your name or handle if you want attribution

Please avoid accessing, changing, or exposing data that does not belong to you.

## What happens next

Reports are handled on a best-effort basis. Response and remediation time depend on severity, reproducibility, project maturity, maintainer availability, and the complexity of the fix.

When appropriate, we will coordinate disclosure with the reporter and avoid publishing exploit details before a reasonable fix or mitigation is available.

## Scope

Security reports are useful when they describe a concrete issue in code or infrastructure maintained by Cunilab, such as:

- authentication or authorization bypass
- unintended data or secret exposure
- remote code execution
- sandbox or isolation escape
- realistic cryptographic weakness
- supply-chain or dependency-confusion risk caused by Cunilab-controlled configuration

Reports are generally less actionable when they concern:

- purely theoretical issues without a realistic attack path
- vulnerabilities that exist only in an unrelated third-party dependency
- self-XSS without impact on another user
- denial of service requiring control of the local machine

Project-specific security policies take precedence over this organization default.

## Recognition

When appropriate, reporters can be credited in release notes or security advisories unless they prefer to remain anonymous.
