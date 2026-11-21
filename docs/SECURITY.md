# Security

DevImpact takes the protection of accounts, repositories, and users seriously.

## Never commit secrets

Do not add any of the following to a repository:

- Passwords or recovery codes.
- Personal access tokens, OAuth secrets, or API keys.
- Private keys, signing keys, or certificates containing private material.
- Database credentials or private connection strings.
- Private user data or confidential business information.

Use approved secret-management features only when a workflow or integration has been explicitly authorized. Do not create secrets or enable automation as part of an ordinary documentation change.

## Repository visibility

Treat public repositories as fully public. Do not assume that deleting a file removes a secret from Git history. If a credential is exposed, revoke or rotate it immediately and assess the affected systems.

Keep internal information in the designated private repositories. Review links and attachments before publishing them.

## Account protection

- Use strong, unique authentication credentials.
- Enable two-factor authentication on the GitHub account and organization where available.
- Review connected applications and repository permissions periodically.
- Grant only the permissions needed for an approved task.
- Do not share authentication codes or recovery credentials.

## Reporting a vulnerability

If you discover a security issue affecting a DevImpact repository or service, avoid posting exploit details or sensitive data publicly. Contact the organization owner through GitHub and provide a concise description, affected repository or service, impact, and safe reproduction details.

Do not test vulnerabilities against systems or accounts without authorization.

## Scope

This document describes security practices for the GitHub-based DevImpact ecosystem. It does not promise a dedicated security response team, a service-level agreement, or a vulnerability bounty program.
