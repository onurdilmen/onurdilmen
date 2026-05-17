# Security Policy

## Supported

This repository hosts a personal profile README. It contains no secrets, no
runtime code beyond two harmless GitHub Actions workflows (snake + metrics),
and no user data.

## Reporting a vulnerability

If you discover a security issue in:

- One of my **public repositories**: please email me at
  **onurdilmen@teknoweb.net** with details. Do not open a public issue.
- One of my **products in production** (e-shipsupply.com, teknoweb.net, etc.):
  please email **security@teknoweb.net**. I treat coordinated disclosure
  seriously and respond within 48 hours.

## Scope I care about

- Authentication bypass / privilege escalation in shipped products
- Information disclosure (PII, internal config, secrets)
- Injection (SQL, command, header, template)
- SSRF, XXE, deserialization
- Supply chain (compromised dependencies, malicious commits)

## Out of scope

- Theoretical attacks without a working PoC
- Issues that require the user to install malicious software locally
- Self-XSS without a meaningful chain
- Outdated SSH ciphers on a sandbox / staging endpoint
- Missing `X-Frame-Options` on a non-sensitive marketing page

## Hall of Fame

Names of people who reported valid issues (with their permission) will be added
here. Thanks in advance to anyone who takes the time.

---

_This security policy follows the spirit of
[disclose.io](https://disclose.io/) — good-faith research is welcome._
