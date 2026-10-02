# Security

## Reporting a problem

Tell a maintainer privately, through GitHub — never in an issue, a pull request or a commit
message, which more people and tools read than the problem needs.

## Never in a repository

Secrets and signing material: API keys and config files that hold them (`*.xcconfig` with keys,
`.env*`), App Store Connect keys (`*.p8`), certificates and keys (`*.p12`, `*.cer`, `*.pem`),
provisioning profiles. Each repository's `.gitignore` keeps them out.

If one was committed, removing it in a new commit is not enough — it stays in the history. Revoke
or rotate it first, then tell a maintainer.

## AI tools

Secrets, signing material and users' personal data are never pasted into an AI tool or opened by one.
