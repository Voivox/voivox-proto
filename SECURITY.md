# Security Policy

Voivox is pre-alpha. Please do not publicly disclose suspected vulnerabilities until we have
had a reasonable chance to investigate and fix them.

## Reporting

Use GitHub Private Vulnerability Reporting when available for this repository. If it is not
available, open a minimal public issue asking for a private security contact without including
technical exploit details.

## Scope

In scope:
- authentication, authorization, sessions, and account recovery
- E2EE key handling, encrypted local storage, and device transfer
- message, media, bot, notification, and voice authorization
- privacy leaks in logs, telemetry, exports, and moderation workflows
- CI/CD or dependency supply-chain risks

Out of scope:
- denial-of-service attacks that require large-scale traffic
- social engineering
- attacks requiring physical access to an unlocked developer machine

Do not test against real users, scrape data, persist secrets, or run destructive tests.
