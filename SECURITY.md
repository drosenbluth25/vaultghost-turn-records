# Security Policy

## Scope

This repository publishes example turn records that follow the `VaultGhost.TurnRecord.v1` schema. The contents are documentation/specification‑only and contain placeholder digest material and simulated proof metadata. They are not a production verifier and are not a verified evidence chain over real captured content.

## Evidence Boundary

VaultGhost verifies records within a captured boundary. It can verify hashes, signatures, schemas, timestamps, declared metadata, and replayable artifacts. It does not claim visibility into hidden model weights, provider-side logs, undisclosed system prompts, or private infrastructure.

A valid signature is not trusted identity. Internal consistency is not provenance.

## Reporting a Vulnerability

If you believe you have found a security‑relevant issue in this repository — for example, a misleading claim about cryptographic content, an inconsistency between a published digest and the artifact it claims to attest to, or a defect in the schema as published here — please report it privately rather than opening a public issue.

Open a private security advisory via GitHub:

- Repository: https://github.com/drosenbluth25/vaultghost-turn-records
- Use the “Report a vulnerability” option under the repository’s Security tab.

Please include:

- A description of the issue and why you believe it is security‑relevant.
- The specific file(s) and line(s) involved.
- Steps to reproduce or to demonstrate the claim, where applicable.
- Any suggested remediation.

## Out of Scope

- The placeholder/simulated nature of the artifacts in this repository is documented in `README.md` and is not itself a vulnerability.
- This repository does not host any service, build pipeline, or runtime; classes of issues that depend on a deployed system are out of scope here.

## No Legal Conclusions

This security policy describes how to report issues. It does not, and is not intended to, make any legal claim about the records, their contents, or their evidentiary status.
